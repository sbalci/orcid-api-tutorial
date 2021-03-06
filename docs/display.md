#7. DISPLAY: PRESENTING ORCID IN YOUR SYSTEM

##Display ORCID iDs

Researchers want to know that using their iD in your system has had some effect. The best way to signal that the collected iD is actually put to use is to display it - in your web applications, in publications, with funding awards, etc.

For authenticated iD's show the iD icon followed by the full iD URI, linked to the iD URI:

<a href="https://orcid.org/0000-0002-1825-0097"><img alt="ORCID iD" class="icon" src="http://orcid.org/sites/default/files/images/orcid_16x16(1).gif" style="width:16px; height:16px; margin-right:4px; margin-left:4px">https://orcid.org/0000-0002-1825-0097</a>

For more details, see our [Trademark and iD Display Guidelines](https://orcid.org/trademark-and-id-display-guidelines)

<img src="../images/07_1_kaken_profile_system.png" width="600" alt="ORCID iD displayed on Kaken Profile System for SUENAGA Kiyotake" />
<br>
<br>
<img src="../images/07_1_Orcid_id_journal_functional_ecology.png" width="600" alt="ORCID iD displayed in Journal of Functional Ecology article" />

##Presenting the ORCID OAuth screen & redirect pages
In order to provide a consistent experience for users, we recommend following the guidelines below for presenting ORCID OAuth in your system. For more details, see our help doc on [Presenting OAuth](http://members.orcid.org/api/oauth/presenting-oauth).

###1. Use a button or link to connect users to ORCID via OAuth
See [example buttons and links](http://members.orcid.org/api/oauth/presenting-oauth#use-button)
<br>
<br>
<img src="../images/07-2_link-id-button.png" width="400" alt="Example manuscript submission form with 'Create or Connect your iD' button" />
###2. Include text describing ORCID and a link to the ORCID website
See [sample text](http://members.orcid.org/api/oauth/presenting-oauth#include-text)
<br>
<br>
<img src="../images/07-2_orcid-text.png" width="400" alt="Example manuscript submission form with info about ORCID" />
###3. Present the OAuth sign-in screen as a popup or modal window
The OAuth screen is designed to look best at a maximum width of 500px.
<br>
<br>
<img src="../images/07-2_oauth.png" width="300" alt="Example OAuth authorization screen" />
###4. Provide an appropriate redirect page and close the OAuth window
Remember that users can either authorize or deny access - make sure to show a different message for each case.
<br>
<br>
<img src="../images/07-2_redirect.png" width="300" alt="Example OAuth redirect screen" />
