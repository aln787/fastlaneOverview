##FastLane Mobile Automation
###_Removing the pain of releasing your mobile application_
![](images/CapitalOneFastLane.png)
<p>
	<small><a href="https://twitter.com/alexniderberg">@AlexNiderberg</a></small><br/>
	<small>Software Engineer - Capital One Mobile</small>
</p>


###Presentation Objectives
- Provide insight into tools speed-up mobile application development
- Get you excited to build out a Fastlane set-up for your app!


<img src="images/Alex_and_Catelyn-CryatalMt-WA.png" height="600">


<img src="images/CapitalOneLabs_Overview.png" height="600">
<br>
<small><a href="https://capitalonecareers.com/">Capital One</a></small>


<img src="images/CapitalOneLabs_Work.png" height="600">
<br>
<small><a href="https://www.capitalonelabs.com/#/about">Capital One Labs</a></small>

---

![](images/fastlane_logo.png)


####Fastlane Tools
![](images/intro-fastlane-tree.png)

- [Details](https://fastlane.tools/)


![](images/withFastLane/FastlaneTools.png)


![](images/withFastLane/FastLaneAndriodBeta.png)


![](images/withFastLane/FastlaneFabric.png)


![](images/fastlane_logo.png)

####Has an active / inviting community
#####*Example Issues:*
- [Resigning issue](https://github.com/fastlane/fastlane/issues/3934#issuecomment-201253429)
- [pilot submission failure](https://github.com/fastlane/fastlane/issues/3982#issuecomment-203542842)
- [Abstraction attempts](https://github.com/fastlane/fastlane/issues/3920#issuecomment-201247917)
- [Request for a multi app template](https://github.com/fastlane/fastlane/issues/327)
- [Example Lanes](https://github.com/fastlane/fastlane/issues/428)
- [Running with no Fastfile](https://github.com/fastlane/fastlane/issues/1404)

---

#New iOS App set-up 
###_(without fastlane)_


![](images/itunesAndDevPortal/1-Nucleus_ITC.png)


![](images/itunesAndDevPortal/2-Nucleus_ITC-AppInfo.png)


![](images/itunesAndDevPortal/3-Nucleus_ITC-SubmitToAppStore.png)


![](images/itunesAndDevPortal/4-Nucleus_ITC-SubmitToAppStore-1.png)


![](images/itunesAndDevPortal/5-Nucleus_ITC-SubmitToAppStore-2.png)


![](images/itunesAndDevPortal/6-Nucleus_ITC-SubmitToAppStore-3.png)


![](images/itunesAndDevPortal/7-Nucleus_ITC-SubmitToAppStore-4.png)


###Making Progress
<iframe src="https://giphy.com/embed/l41lIioP4RFRmIVB6?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- dogRunning-afv-funny-fail-lol-l41lIioP4RFRmIVB6 -->


![](images/itunesAndDevPortal/8-Nucleus_DevPortal-SelectTeam.png)


![](images/itunesAndDevPortal/9-Nucleus_DevPortal-Menu.png)


![](images/itunesAndDevPortal/10-Nucleus_DevPortal-CreateNew-AppID.png)


![](images/itunesAndDevPortal/11-Nucleus_DevPortal-CreateNew-AppID-1.png)


![](images/itunesAndDevPortal/12-Nucleus_DevPortal-CreateNew-AppID-2.png)


![](images/itunesAndDevPortal/13-Nucleus_DevPortal-CreateNew-ProvisioningProfile.png)


![](images/itunesAndDevPortal/14-Nucleus_DevPortal-CreateNew-ProvisioningProfile-1.png)


![](images/itunesAndDevPortal/15-Nucleus_DevPortal-CreateNew-ProvisioningProfile-2.png)


![](images/itunesAndDevPortal/16-Nucleus_DevPortal-CreateNew-ProvisioningProfile-3.png)


![](images/itunesAndDevPortal/17-Nucleus_DevPortal-CreateNew-ProvisioningProfile-4.png)


![](images/itunesAndDevPortal/18-Nucleus_DevPortal-CreateNew-ProvisioningProfile-5.png)


![](images/itunesAndDevPortal/19-Nucleus_DevPortal-CreateNew-ProvisioningProfile-6.png)


![](images/itunesAndDevPortal/20-Nucleus_DevPortal-CreateNew-ProvisioningProfile-7-Download.png)


###This is taking too long!!
<iframe src="https://giphy.com/embed/3SCKnFChtClxK?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- MindyProjectI-HaveStandards-life-up-3SCKnFChtClxK -->

---

#Releasing an iOS app
###_(Without Fastlane)_


##Navigate to the project
![](images/itunesAndDevPortal/21-Nucleus_Xcode.png)


###Open the xc project or workspace
![](images/itunesAndDevPortal/22-Nucleus_Xcode-Workspace.png)


###Update the build number
![](images/itunesAndDevPortal/23-Nucleus_Xcode-General.png)


###Select generic iOS Device
![](images/itunesAndDevPortal/24-Nucleus_Xcode-SelectGenericDevice.png)


###Select the team
![](images/itunesAndDevPortal/25-Nucleus_Xcode-SelectTeam.png)


![](images/itunesAndDevPortal/26-Nucleus_Xcode-SelectSigningIdendity.png)


###Update the signing identity and provisioning profile
![](images/itunesAndDevPortal/27-Nucleus_Xcode-SelectPreferences.png)


###So many steps
<iframe src="https://giphy.com/embed/lYKvaJ8EQTzCU?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- jon-stewart-why-lYKvaJ8EQTzCU -->


###Login to the developer portal
![](images/itunesAndDevPortal/28-Nucleus_Xcode-SelectTeam.png)


###Archive your app
![](images/itunesAndDevPortal/29-Nucleus_Xcode-ArchiveRequest.png)


###Archive output
![](images/itunesAndDevPortal/30-Nucleus_Xcode-ArchiveSuccess.png)


###Submit to the app store
![](images/itunesAndDevPortal/31-Nucleus_Xcode-ArchiveShareSettings.png)


###Select the team again
![](images/itunesAndDevPortal/32-Nucleus_Xcode-ArchiveShareSettings-1.png)


###Help!!!
<iframe src="https://giphy.com/embed/H2VD6psStWlJ6?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- Help-H2VD6psStWlJ6 -->

---

![](images/fastlane_logo.png)
##To the rescue


##Fastlane CLI
```
fastlane actions
fastlane action sigh
```

![](images/sighAction.png)


##Existing lane description
```
fastlane list
```

![](images/fastlaneLanes.png)


##New Project Set-up
```
fastlane init
```
![](images/fastlaneInit.png)

---

##How we are using Fastlane at Capital One
![](images/CapitalOneFastLane.png)


####Teams we have already automated
![](images/FastLaneAutomatedTeams.png)

- [Details](https://github.kdc.capitalone.com/Nucleus/JenkinsDSL/wiki#fastlane-automated-teams)


### Working to build a community within the company
<img src="images/withFastLane/C1FastLaneCollaboration.png" height="400">


### Empowering teams to manage their own jobs and enhance the overall capabilities
<img src="images/withFastLane/TeamsAreManagingTheirOwnJobs.png" height="400">


####Infrastructure from one of our internal teams
![](images/LabsBuildInfrastructureNoBoarder.png)

---

![](images/fastlane_logo.png)
##In action


##Adding a new App to the ADP and iTC
![](images/addA_newAppTo_itc_and_adp.gif)


##Testing your app
<img src="images/test.gif">


##Deploying to iTunes-Connects Test-flight
<img src="images/testFlight-iTunesConnect.gif">


##Travis CI Fastlane test
![](images/travisTest.gif)

---

![](images/tips.png)


##Proxy Configuration
```
DELIVER_ITMSTRANSPORTER_ADDITIONAL_UPLOAD_PARAMETERS="-t DAV" deliver
export proxy=<your proxy>
export http_proxy=$proxy
export https_proxy=$proxy
```

- [Upload via Proxy ](https://github.com/fastlane/fastlane/tree/master/deliver#http-proxy)


##Add the proxy to the transporter app that is embedded in Xcode
```
vi "$(xcode-select -p)/../Applications/Application Loader.app/Contents/itms/java/lib/net.properties"
```

![](images/configureProxy.png)


###Transporter Endpoints
![](images/transporterEndPoints.png)

- [Endpoints PDF](https://wmiphone.files.wordpress.com/2013/07/itunes_store_transporter_quick_start_guide_v2.pdf)


##.env file 
####_(in addition to Appfile)_
```
.env
.env.enterprise
```

![](images/env.png)

- [Example](https://github.com/aln787/fastlaneExample/tree/master/fastlane)


##Appfile
![](images/appfile.png)

---

##Integrations
![](images/slack_logo_wide.png)


##Configure WebHook
![](images/slackConfigureWebHook.png)


##Resulting SLACK_URL
![](images/slackConfigureWebHook-result.png)


##Slack Action
```
SLACK_URL='https://hooks.slack.com/services/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'
```

![](images/slackAction.png)


##Example Channel
![](images/FastLaneSlackStatusMessages.png)

- https://ios-dev-camp-dc.slack.com/messages/build-status/

---

![](images/fastlane_logo.png)

#Hockey App Support


![](images/hockeyApp/HockeyAppAppsAPI.png)


![](images/hockeyApp/HockeyAppVersionsAPI.png)

---

#New iOS app set-up
###_(with)_

![](images/fastlane_logo.png)


###Using Fastlane With our shared Fastfile Steps are automated
- Apple developer portal
  - Creates the App ID
  - Sets entitlements 
  - Generates provisioning profiles
- iTunes-connect
  - Adds a new app with the details your provided as environment variables

```
$ fastlane ios addNewApp
```

![](images/withFastLane/fastLaneIosProfiles.png)


##Example
```
## 1. Set Variables
# ITC Variables
export APP_ID="com.capitalone.nucleus-ios-pilot-prod"
export APP_Name="Nucleus iOS Pilot Prod"
export SKU="LABS-NUCLEUS"
export PROVISIONING_NAME="Nucleus iOS Pilot Prod"

# Project Build Variables
export WORKSPACE=" "
export SCHEME="nucleus-ios-pilot"
export PROJECT_FILE_PATH="nucleus-ios-pilot"
export PROJECT_NAME="nucleus-ios-pilot"
export PROVISIONING_PROFILE_PATH="AppStore_com.capitalone.nucleus-ios-pilot-prod.mobileprovision"

# Shared Config for All Apps Using the Labs App Store License
export TEAM_ID="NR7RF5923T"
export CERT_ID="54ZX25X658"
export KEY_CHAIN_PATH="/Users/$USER/Library/Keychains/Expiration-6-22-16__CERT_ID-54ZX25X658__TEAM_ID-NR7RF5923T.keychain"
export CODESIGNING_IDENTITY="iPhone Distribution: Capital One Financial Corporation (NR7RF5923T)"
export PROXY_URL="internal-innovation-httpproxy-1417235642.us-east-1.elb.amazonaws.com:80"
export slackErrorMessage="ERROR building and deploying Nucleus-ios to iTunes Connect."
export slackSuccessMessage="Successfully built Nucleus-ios and deployed to iTunes Connect."
export SLACK_URL="https://hooks.slack.com/services/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"
export FASTFILE_URL="https://github.kdc.capitalone.com/raw/xvo202/fastlaneSharedFastfile/v0.3.4/Fastfile"

# Values to update for local releases
export USER_Name="<email address>"
export FAST_PASS=$FASTLANE_KEYPASS_EXP_6_22_16_CERT_ID_54ZX25X658_TEAM_ID_NR7RF5923T

## 2. Retrieve the shared astfile
# Getting and Injecting the Shared FastLane Config
cd $PROJECT_FILE_PATH && \
curl $FASTFILE_URL > Fastfile && \
if [ ! -d "fastlane" ]; then
  mkdir fastlane
fi && \
mv -f Fastfile fastlane/
# Print Fast File Contents
more fastlane/Fastfile

## 3. Set the proxy
# Proxy Configuration
export DELIVER_ITMSTRANSPORTER_ADDITIONAL_UPLOAD_PARAMETERS='-t DAV' && \
export http_proxy=$PROXY_URL && \
export https_proxy=$PROXY_URL

## 4. Run Fastlane
# Fastlane - Download Signing Identities, Build and Deploy
fastlane ios profiles
```
- [Shared Fastfile Repository](https://github.kdc.capitalone.com/xvo202/fastlaneSharedFastfile)


##Wow, that was easy!
<iframe src="https://giphy.com/embed/vBVCam8nE7uxy?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- GetTheBabby-vBVCam8nE7uxy -->

---

##Automation Walk through 
#####_(Github webhook triggered Jenkins FastLane build that uploads to iTunes connect)_


![](images/itunesAndDevPortal/groupLoopGitPush.png)


####The easy way!!
<iframe src="https://giphy.com/embed/qyCDVJBPdBET6?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- penguinSlide_hereWeGo-9UCStxAde7lK or PT88CWkUepFpS or qyCDVJBPdBET6 or rFrju0XGospHi or l49FvM5VWIPnyiyVW-->


![](images/withFastLane/10-Jenkins-Stable-Output.png)


![](images/withFastLane/11-Jenkins-Stable-Output-2.png)


<iframe src="https://giphy.com/embed/tbAY4hlx9fzjy?hideSocial=true" width="400" height="400" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- Flying?-tbAY4hlx9fzjy -->


![](images/withFastLane/12-Jenkins-Stable-Output-3.png)


![](images/withFastLane/13-Jenkins-Stable-Output-4.png)


![](images/withFastLane/14-Jenkins-Stable-Output-5.png)


![](images/withFastLane/15-Jenkins-Stable-Output-6.png)


![](images/withFastLane/16-Jenkins-Stable-Output-7.png)


![](images/withFastLane/17-Jenkins-Stable-Output-8.png)


![](images/withFastLane/18-Jenkins-Stable-Output-9-success.png)


![](images/withFastLane/19-itc-processing.png)


![](images/withFastLane/20-itc-success.png)


####Slack Notification
![](images/FastLaneSlackStatusMessages.png)


###Success!!!
<iframe src="https://giphy.com/embed/PzOm3LPWu7fJS?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- victory-reaction-jennifer-lawrence-PzOm3LPWu7fJS -->
<!-- ####Now we are getting some love! Much better!! -->
<!-- <iframe src="https://giphy.com/embed/2ur8NS5TYQmK4?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe> -->
<!-- CuddleFest-2ur8NS5TYQmK4 -->


![](images/FastLaneBranchingStrategy.png)

---

##Jenkins DSL
![](images/fastlane_plus_jenkins.png)


###Configure a seed job
![](images/ConfigureSeedJobPart1.png)


###Configure a seed Job continued
[![](images/ConfigureSeedJobPart2.png)](https://github.kdc.capitalone.com/Nucleus/JenkinsDSL)

- [Jenkins DSL Config Repo](https://github.kdc.capitalone.com/Nucleus/JenkinsDSL) 


####Example Generated iOS Build and Deploy Job
![](images/withFastLane/6-Jenkins-StableConfig.png)


####Repo Info
![](images/withFastLane/7-Jenkins-StableConfig-2.png)


####Shell Script - Part 1
![](images/withFastLane/8-Jenkins-StableConfig-3.png)


####Shell Script - Part 2
![](images/withFastLane/9-Jenkins-StableConfig-4.png)

---

###Thank you!!! 
![](images/FrozenVictory.jpg)

<!-- <iframe src="https://giphy.com/embed/vBVCam8nE7uxy?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe> -->

---

#Appendix

---

![](images/fastlane_logo.png)

#Ionic Support 
##_(iOS and Android)_

