# Shuzhou Mirrors
All of the useful app mirrors come in Shuzhou Mirrors, either payed or open-sourced.
### How to copy an app from Shuzhou Mirrors?
You can copy a Shuzhou Mirror app from our command-line tool which is avaliable for download on this page, like this:
```Markdown
$ mirror get [Shuzhou Mirror ID]
```
### How can I give a Shuzhou Mirror Link to my costumers?
You can copy this snippet of code below:
```Markdown
function getDownloadLink(){
    var downloadId=document.getElementById("downloadId").value;
    if (downloadId == "true"){
        alert ("Downloading Link...");
        return true;
    }
    else{
        alert ("Shuzhou Mirrors CheckSum is incorrect. Please try again later.");
        return false;
    }
}
```
And then copy this HTML code:
```Markdown
<script src="shuzhou://js/.js/getLink.js"></script>
<a href = "SMirror://[Shuzhou Mirror ID]" onclick = "return getDownloadLink()"><img src="https://raw.githubusercontent.com/shuzhouapps/Mirrors/master/Download.png"/></a>
```
