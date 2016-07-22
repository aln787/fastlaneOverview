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


<img src="images/CapitalOneLabs_Work.png" height="600">
<br>
<small><a href="https://www.capitalonelabs.com/#/about">Capital One Labs</a></small>

---

##Why
![](images/fastlane_logo.png)


####Fastlane Tools
![](images/intro-fastlane-tree.png)

- [Details](https://fastlane.tools/)


##Time Saving
![](images/hoursSaved.png)


![](images/withFastLane/FastLaneAndriodBeta.png)


![](images/withFastLane/FastlaneFabric.png)


![](images/fastlane_logo.png)

####Has an active / inviting community
- https://github.com/fastlane/fastlane 

#####*Example Issues:*
- [Resigning issue](https://github.com/fastlane/fastlane/issues/3934#issuecomment-201253429)
- [Request for a multi app template](https://github.com/fastlane/fastlane/issues/327)


##Fix-issue
![](images/Fix-issue.png)

---

#New iOS App set-up 
###_(without fastlane)_


![](images/itunesAndDevPortal/8-Nucleus_DevPortal-SelectTeam.png)


![](images/itunesAndDevPortal/9-Nucleus_DevPortal-Menu.png)


![](images/itunesAndDevPortal/10-Nucleus_DevPortal-CreateNew-AppID.png)


![](images/itunesAndDevPortal/11-Nucleus_DevPortal-CreateNew-AppID-1.png)


![](images/itunesAndDevPortal/12-Nucleus_DevPortal-CreateNew-AppID-2.png)


###Making Progress
<iframe src="https://giphy.com/embed/l41lIioP4RFRmIVB6?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- dogRunning-afv-funny-fail-lol-l41lIioP4RFRmIVB6 -->


![](images/addNewAppToItc.png)


![](images/newAppAddedToItc.png)

---

#Releasing an iOS app
###_(Without Fastlane)_


####Apple Developer Portal
![](images/itunesAndDevPortal/8-Nucleus_DevPortal-SelectTeam.png)


![](images/itunesAndDevPortal/9-Nucleus_DevPortal-Menu.png)


![](images/itunesAndDevPortal/13-Nucleus_DevPortal-CreateNew-ProvisioningProfile.png)


![](images/itunesAndDevPortal/14-Nucleus_DevPortal-CreateNew-ProvisioningProfile-1.png)


![](images/itunesAndDevPortal/15-Nucleus_DevPortal-CreateNew-ProvisioningProfile-2.png)


![](images/itunesAndDevPortal/16-Nucleus_DevPortal-CreateNew-ProvisioningProfile-3.png)


![](images/itunesAndDevPortal/17-Nucleus_DevPortal-CreateNew-ProvisioningProfile-4.png)


![](images/itunesAndDevPortal/18-Nucleus_DevPortal-CreateNew-ProvisioningProfile-5.png)


![](images/itunesAndDevPortal/19-Nucleus_DevPortal-CreateNew-ProvisioningProfile-6.png)


![](images/itunesAndDevPortal/20-Nucleus_DevPortal-CreateNew-ProvisioningProfile-7-Download.png)


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


###This is taking too long!!
<iframe src="https://giphy.com/embed/3SCKnFChtClxK?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- MindyProjectI-HaveStandards-life-up-3SCKnFChtClxK -->


####iTunes-connect - Submit your app for review
![](images/itunesAndDevPortal/1-Nucleus_ITC.png)


![](images/itunesAndDevPortal/2-Nucleus_ITC-AppInfo.png)


![](images/itunesAndDevPortal/3-Nucleus_ITC-SubmitToAppStore.png)


![](images/itunesAndDevPortal/4-Nucleus_ITC-SubmitToAppStore-1.png)


![](images/itunesAndDevPortal/5-Nucleus_ITC-SubmitToAppStore-2.png)


![](images/itunesAndDevPortal/6-Nucleus_ITC-SubmitToAppStore-3.png)


![](images/itunesAndDevPortal/7-Nucleus_ITC-SubmitToAppStore-4.png)


###Help!!!
<iframe src="https://giphy.com/embed/H2VD6psStWlJ6?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- Help-H2VD6psStWlJ6 -->

---

![](images/fastlane_logo.png)
##To the rescue
- [follow along](https://github.com/aln787/fastlaneExample#getting-started-if-you-dont-have-ruby-230-or-bundler-installed-follow-the-steps-below)


##Fastlane CLI
```
fastlane actions
fastlane action sigh
```

![](images/sighAction.png)


##New Project Set-up
```
fastlane init
curl -k https://raw.githubusercontent.com/aln787/fastlaneExample/master/fastlane/Fastfile > fastlane/Fastfile
curl -k https://raw.githubusercontent.com/aln787/fastlaneExample/master/fastlane/.env > fastlane/.env
```
![](images/fastlaneInit.png)


##Existing lane description
```
fastlane list
fastlane lanes
```

![](images/fastlaneLanes.png)

#New iOS app set-up
###_(with)_

![](images/fastlane_logo.png)


###Using Fastlane With our shared Fastfile Steps are automated
- Apple developer portal
  - Creates the App ID
  - Sets default entitlements 
- iTunes-connect
  - Adds a new app with the details your provided as environment variables


##Adding a new App to the ADP and iTC
```
fastlane ios addNewApp
```

![](images/addA_newAppTo_itc_and_adp.gif)


##Wow, that was easy!
<iframe src="https://giphy.com/embed/vBVCam8nE7uxy?hideSocial=true" width="680" height="567" frameborder="0" class="giphy-embed" allowfullscreen=""></iframe>
<!-- GetTheBabby-vBVCam8nE7uxy -->

---

##How we are using Fastlane at Capital One
![](images/CapitalOneFastLane.png)


####Teams we have already automated
![](images/FastLaneAutomatedTeams.png)

- [CashTapp](https://itunes.apple.com/us/app/cashtapp/id1085845144?mt=8)


##CashTapp
![](images/CashTapp.png)


### Working to build a community within the company
<img src="images/withFastLane/C1FastLaneCollaboration.png" height="400">


####Internal Infrastructure
![](images/LabsBuildInfrastructureNoBoarder.png)

---

![](images/fastlane_logo.png)
##In action


##Testing your app
```
git add . && git stash && git checkout master
fastlane ios test
```

<img src="images/test.gif">


##Deploying to HockeyApp
```
fastlane hockeyApp --env enterprise
```

- https://rink.hockeyapp.net/manage/apps/361738


##Deploying to iTunes-Connect Test-flight
```
fastlane ios beta
```

<img src="images/testFlight-iTunesConnect.gif">

- [View in iTunes-Connect]https://itunesconnect.apple.com/WebObjects/iTunesConnect.woa/ra/ng/app/1125513788/activity/ios/builds


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

![](images/slack_logo_wide.png)
##Integration


##[Configure WebHook](https://ios-dev-camp-dc.slack.com/apps/manage/custom-integrations)
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

#Hockey App Distribution


##Why Hockey App
![](images/hockeyApp/HockeyAppAppsAPI.png)


![](images/hockeyApp/HockeyAppVersionsAPI.png)

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

---

![](images/fastlane_logo.png)
##Next Steps
- Go Migrate your application's CI/CD process to Fastlane
- Being interacting with the community (https://github.com/fastlane/fastlane)
- Start contributing or writing your own [plugins](https://github.com/fastlane/fastlane/blob/master/fastlane/docs/Plugins.md)

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
