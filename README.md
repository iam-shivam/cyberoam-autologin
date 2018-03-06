# cyberoam-autologin
<b><i>Got a lot of Cyberoam IDs, Want to auto-login another when one ends and too lazy to login yourself?</i></b>
<br/><br/>
It takes a list of IDs(given to you by your college or whoever uses Cyberoam) and a password and autologins those IDs.
As soon as you open the login portal, it checks through the list of IDs and automatically logins. If the logged-in ID gets it's data exceeded, logged off or periodic time over, it automatically switches over to next ID.
<br/><br/>
<b>How to run it?</b>
- I use <b>tampermonkey</b> on Google Chrome. You can use any similar browser extension.
- Create a new script and copy everything there.
- In the predefined options, set your cyberoam address for login page to @match. For example,<br/>
  @match    http://175.16.89.16:8888/<br/>
  This is <b>important</b> because this will tell where to run the script.
- Set your list of common passwords. I have already set a few example ones and marked the location with a comment.
- Set starting id. Marked.
- Set ending id. Marked.
- Open your cyberoam login page.
- <i>Thank Me Later ;)</i>
- <b>NOTE: You need working internet when you first launch the script(It needs to download jQuery). So, after adding script in tampermonkey, make sure your internet is working and then open the login page. <br> Still not clear? Message me. </b>
<br>
<h5> <u>Disclaimer:</u> I am not responsible for anything bad (like getting suspended or debarred from college or maybe your friends and girlfriend leaving you for exceeding their cyberoam data. Who knows man?) happening to you due to this script. </h5>

<h2> Did you check my Cyberoam-Cracker yet? : https://github.com/iam-shivam/cyberoam-cracker</h2>
