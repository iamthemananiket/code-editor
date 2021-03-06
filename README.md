# code-editor
## Team *Coderscode*

**Idea** - A web-based front-end code editor, that provides a live preview of the HTML/CSS/JS code input in the editor.
This editor would be indisputably real-time as the developer won't have to press any button to load the preview as the editor will load it after every keypress.

**Reason for this idea** - As DigitalOcean is know to be a cloud platform exclusively for *developers*, we chose this idea as it would benefit several front-end web developers including us.
A web-app of this kind would need very low latency to improve the site's UX. Since DigitalOcean's data center is now in Bangalore, it would be a very promising platform to host out web-app.

**Using the web app** - 
1. Visit http://139.59.0.244/ to use our web-app that has been hosted on a 512MB/20GB/Ubuntu16 droplet located in Bangalore data center.
2. You now have to load a project that is currently existing in the server. Hence, type one of the following project names into the text box.
i. jQuery-Todo-master
ii. Crossword
3. You can then edit the HTML/CSS/JS from the code-editor and get to view the live preview of the code.

The project uses Js for most event trigfering and handling. PhP for regexing, responding and displaying the result of the source code on the frame.

***Screenshots***
https://drive.google.com/open?id=0B0VcEe5WTNdoczFEb3lGQTFTRFU
https://drive.google.com/open?id=0B0VcEe5WTNdoN0NBZy01X3g3bm8
https://drive.google.com/open?id=0B0VcEe5WTNdocHpkRzh6QlB4ajg

We compared the performance of the our DigitalOcean web app to one that was hosted on Microsoft Azure.
The serverside HTML/CSS/JS files took an average of 350ms to load for Azure whereas those on DigitalOcean took just 60ms.
