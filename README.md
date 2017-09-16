# GitLagos

 GitLagos is an app that retrieves the list of Java developers in Lagos, Nigeria using the GitHub API and display some of their data in the apps's 
 Interface.
 
Each item on the list consists of:
- User’s profile image
- User’s GitHub username.

Clicking each item on the list would show their profile details in which the profile screen contains:
- Username
- Profile photo
- Github profile URL and
- a button to share their profile.

Clicking the button launches a share intent which has the content “Check out this awesome developer @github_username, github_profile_url.”
 Also, clicking on the Github url launches the browser and link to their Github page.

Heavy network request to the server was done using the Android <a href="https://developer.android.com/training/volley/index.html">Volley</a> library while images were displayed 
using the Sqareup <a href="http://square.github.io/picasso/">Picasso</a> library.

Below are the screenshots of the app's UI.
<div id="image-table">
    <table>
        <tr>
             <td style="padding:5px">
                <img src="https://i.imgur.com/22A0kML.png" alt="screenshot 1">
             </td>
            <td style="padding:5px">
                <img src="https://i.imgur.com/f5KKRBo.png" alt="screenshot 2"
                title="No connection preview">
              </td>
             <td style="padding:5px">
                <img src="https://i.imgur.com/NwTdKmt.png"alt="screenshot 3">
              </td>
        </tr>
    </table>
     <table>
        <tr>
            <td style="padding:5px">
                <img src="https://i.imgur.com/8argE6N.png"alt="screenshot 4">
              </td>
            <td style="padding:5px">
                <img src="https://i.imgur.com/PZqQ2QA.png"alt="screenshot 5">
             </td>
        </tr>
    </table>
</div>

Pre-requisites
--------------

- Android SDK v25
- Android Build Tools v23.0.1
- Android Support Repository v25.3.1

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the "gradlew build" command or use "Import Project" in Android Studio.
