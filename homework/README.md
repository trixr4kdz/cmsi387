### Process Survey:

#### 1)
```
Command: ps aux | grep root

Output:

root             7731   0.0  0.1  2471520   2324   ??  Ss    6:53PM   0:00.02 /System/Library/PrivateFrameworks/AccountPolicy.framework/XPCServices/com.apple.AccountPolicyHelper.xpc/Contents/MacOS/com.apple.AccountPolicyHelper 
root             7691   0.0  0.1  2470996   2632   ??  Ss    6:53PM   0:00.04 /System/Library/CryptoTokenKit/com.apple.ifdreader.slotd/Contents/MacOS/com.apple.ifdreader
root             7643   0.0  0.0  2473148    232   ??  Ss   10:34PM   0:00.04 /usr/libexec/nehelper
root             7572   0.0  0.1  2497900   2492   ??  Ss   10:07PM   0:00.16 /usr/libexec/amfid
root             7550   0.0  0.0  2471252   1268   ??  Ss    9:58PM   0:00.04 /System/Library/PrivateFrameworks/PackageKit.framework/Resources/installd
root             7549   0.0  0.0  2471524   1344   ??  Ss    9:58PM   0:00.36 aslmanager
root             7548   0.0  0.1  2471888   2224   ??  Ss    9:58PM   0:00.15 /System/Library/PrivateFrameworks/CacheDelete.framework/deleted
root             7523   0.0  0.0  2472544    192   ??  Ss    9:49PM   0:00.07 /System/Library/PrivateFrameworks/CoreSymbolication.framework/coresymbolicationd
root             7520   0.0  0.0  2506732    252   ??  Us    9:49PM   0:00.07 /usr/libexec/sandboxd
root             7514   0.0  0.0  2471772   1264   ??  Ss    9:47PM   0:00.37 sysmond
root             7512   0.0  0.0  2471548    676   ??  Ss    9:47PM   0:00.06 /System/Library/PrivateFrameworks/PerformanceAnalysis.framework/Versions/A/XPCServices/com.apple.PerformanceAnalysis.animationperfd.xpc/Contents/MacOS/com.apple.PerformanceAnalysis.animationperfd
root             7510   0.0  0.0  2471168    176   ??  Ss    9:47PM   0:00.03 /System/Library/PrivateFrameworks/SoftwareUpdate.framework/Resources/suhelperd
root             7500   0.0  0.0  2471824   1312   ??  Ss    9:45PM   0:04.04 /usr/libexec/systemstatsd
root             7492   0.0  0.0  2471284   1248   ??  Ss    9:43PM   0:00.04 /System/Library/Frameworks/Security.framework/Versions/A/XPCServices/com.apple.CodeSigningHelper.xpc/Contents/MacOS/com.apple.CodeSigningHelper
root             7488   0.0  0.2  2503828   6648   ??  Ss    9:43PM   0:02.44 /usr/libexec/coreduetd
root             7487   0.0  0.0  2471496    400   ??  Ss    9:43PM   0:00.02 /usr/libexec/networkd_privileged
root             7483   0.0  0.0  2471692    768   ??  Ss    9:43PM   0:00.10 /usr/libexec/diagnosticd
root             7478   0.0  0.0  2498328   1648   ??  Ss    9:43PM   0:00.19 /System/Library/PrivateFrameworks/WirelessDiagnostics.framework/Support/awdd
root             7477   0.0  0.0  2497804   1996   ??  Ss    9:43PM   0:00.07 /usr/sbin/WirelessRadioManagerd
root             4313   0.0  0.0   404192    344   ??  S    Fri04PM   0:06.38 /Library/DropboxHelperTools/Dropbox_u501/dbfseventsd
root             4312   0.0  0.0   397024     40   ??  S    Fri04PM   0:01.68 /Library/DropboxHelperTools/Dropbox_u501/dbfseventsd
root             3417   0.0  0.0  2496880    316   ??  Ss   Thu11PM   0:00.07 /System/Library/PrivateFrameworks/Noticeboard.framework/Versions/A/Resources/nbstated
root             2363   0.0  0.0  2454900    156   ??  S    Thu04PM   0:00.02 /System/Library/Frameworks/CoreServices.framework/Frameworks/Metadata.framework/Versions/A/Support/mdflagwriter
root             1628   0.0  0.0  2498828    292   ??  Ss   Thu12PM   0:03.78 /usr/libexec/syspolicyd
root              486   0.0  0.1  2515460   2352   ??  Ss   Thu03AM   0:18.86 /System/Library/CoreServices/SubmitDiagInfo server-init
root              400   0.0  0.0  2471004      8 s001  Ss   Thu03AM   0:00.04 login -pfl Trixie /bin/bash -c exec -la bash /bin/bash
root              387   0.0  0.0  2471004      8 s000  Ss   Thu03AM   0:00.05 login -pf Trixie
root              373   0.0  0.0  2472520    192   ??  Ss   Thu03AM   2:37.46 /Library/CoreMediaIO/Plug-Ins/DAL/AppleCamera.plugin/Contents/Resources/AppleCameraAssistant
root              370   0.0  0.0  2470968    464   ??  Ss   Thu03AM   0:00.12 /System/Library/CoreServices/CrashReporterSupportHelper server-init
root              360   0.0  0.0  2497460   1324   ??  Ss   Thu03AM   0:00.37 /System/Library/CoreServices/backupd.bundle/Contents/Resources/TMCacheDelete
root              348   0.0  0.0  2471812    140   ??  Ss   Thu03AM   0:01.09 /usr/libexec/watchdogd
root              341   0.0  0.0  2475572     80   ??  Ss   Thu03AM   0:01.26 /usr/sbin/filecoordinationd
root              332   0.0  0.0  2476988    580   ??  Ss   Thu03AM   0:00.44 /System/Library/CoreServices/sharedfilelistd --enable-legacy-services
root              265   0.0  0.1  2497248   2236   ??  Ss   Thu03AM   0:37.78 /usr/libexec/securityd_service
root              245   0.0  0.0  2505384    560   ??  Us   Thu03AM   0:00.28 /System/Library/Frameworks/OpenGL.framework/Versions/A/Libraries/CVMServer
root              243   0.0  0.1  2498276   3612   ??  Ss   Thu03AM   0:20.47 /usr/libexec/ApplicationFirewall/socketfilterfw
root              240   0.0  0.0  2471004     88   ??  Ss   Thu03AM   0:00.38 /usr/libexec/thermald
root              239   0.0  0.0  2496788    508   ??  Ss   Thu03AM   0:00.26 /usr/libexec/usbd
root              236   0.0  0.0  2471008    200   ??  Ss   Thu03AM   0:00.33 /usr/libexec/corestoraged
root              235   0.0  0.0  2472220    396   ??  Ss   Thu03AM   0:04.47 /usr/sbin/ntpd -c /private/etc/ntp-restrict.conf -n -g -p /var/run/ntpd.pid -f /var/db/ntp.drift
root              228   0.0  0.6  3340168  27164   ??  Us   Thu03AM   4:15.62 /System/Library/Frameworks/CoreServices.framework/Frameworks/Metadata.framework/Versions/A/Support/mds_stores
root              224   0.0  0.0  2501876    796   ??  Ss   Thu03AM   0:01.16 /usr/libexec/lsd runAsRoot
root              211   0.0  0.0  2497980    140   ??  Ss   Thu03AM   0:00.39 /usr/libexec/diskmanagementd
root              175   0.0  0.0  2471516     12   ??  Ss   Thu03AM   0:00.05 /System/Library/Frameworks/PCSC.framework/Versions/A/XPCServices/com.apple.ctkpcscd.xpc/Contents/MacOS/com.apple.ctkpcscd
root              147   0.0  0.0  2504008   1992   ??  Ss   Thu03AM   0:02.65 /System/Library/CoreServices/coreservicesd
root              145   0.0  0.1  2472432   3144   ??  Ss   Thu03AM   0:17.23 /usr/sbin/cfprefsd daemon
root              144   0.0  0.0  2498996    964   ??  Ss   Thu03AM   0:01.16 /System/Library/Frameworks/Security.framework/Versions/A/XPCServices/authd.xpc/Contents/MacOS/authd
root              141   0.0  0.0  2498800   1288   ??  Ss   Thu03AM   0:00.99 /usr/libexec/taskgated -s
root              111   0.0  0.0  2471868   1560   ??  Ss   Thu03AM   0:13.42 /usr/sbin/notifyd
root              110   0.0  0.0  2471540   1016   ??  Ss   Thu03AM   0:00.95 /usr/libexec/AirPlayXPCHelper
root              109   0.0  0.0  2473696   2008   ??  Ss   Thu03AM   5:49.04 /usr/libexec/hidd
root              107   0.0  0.0  2471308     52   ??  Ss   Thu03AM   0:00.03 /usr/sbin/KernelEventAgent
root              106   0.0  0.0  2470992    288   ??  Ss   Thu03AM   0:00.17 /System/Library/CoreServices/logind
root              104   0.0  0.0  2518964    236   ??  Ss   Thu03AM   1:37.43 /System/Library/PrivateFrameworks/GenerationalStorage.framework/Versions/A/Support/revisiond
root               97   0.0  0.0  2471476     12   ??  Ss   Thu03AM   0:00.06 autofsd
root               96   0.0  0.0  2497440   1676   ??  Ss   Thu03AM   0:00.71 /usr/sbin/blued
root               91   0.0  0.1  2500232   2596   ??  Ss   Thu03AM   0:18.09 /usr/sbin/securityd -i
root               89   0.0  0.1  2499540   5744   ??  Ss   Thu03AM   0:25.42 /System/Library/CoreServices/launchservicesd
root               88   0.0  0.1  2499928   5040   ??  Ss   Thu03AM   0:12.20 /System/Library/PrivateFrameworks/ApplePushService.framework/apsd
root               86   0.0  0.0  2471288    356   ??  Ss   Thu03AM   0:00.25 /usr/sbin/wirelessproxd
root               84   0.0  0.1  2512964   5120   ??  Us   Thu03AM   0:18.05 /usr/libexec/opendirectoryd
root               78   0.0  0.0  2496556   1504   ??  Ss   Thu03AM   0:02.02 /usr/libexec/diskarbitrationd
root               75   0.0  0.0  2470976      8   ??  Ss   Thu03AM   0:00.02 /Library/Application Support/Seagate/TBLoopDriveParams
root               71   0.0  0.2  2601132   8872   ??  Ss   Thu03AM   1:49.35 /System/Library/Frameworks/CoreServices.framework/Frameworks/Metadata.framework/Support/mds
root               70   0.0  0.0  2498224   1344   ??  SNs  Thu03AM   0:00.73 /usr/libexec/warmd
root               68   0.0  0.1  2505784   3968   ??  Ss   Thu03AM   0:40.21 /usr/libexec/airportd
root               63   0.0  0.0  2497196   1620   ??  Us   Thu03AM   0:05.21 /System/Library/CoreServices/powerd.bundle/powerd
root               62   0.0  0.1  2501716   3348   ??  Ss   Thu03AM   0:12.61 /usr/libexec/configd
root               57   0.0  0.0  2475288   1732   ??  Ss   Thu03AM   0:32.03 /System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/FSEvents.framework/Versions/A/Support/fseventsd
root               56   0.0  0.1  2505728   2616   ??  Ss   Thu03AM   0:17.65 /usr/libexec/kextd
root               54   0.0  0.0  2473504   1040   ??  Ss   Thu03AM   1:29.63 /usr/sbin/syslogd
root               53   0.0  0.1  2504140   4604   ??  Ss   Thu03AM   0:28.13 /usr/libexec/UserEventAgent (System)
root                1   0.0  0.2  2479816   7768   ??  Ss   Thu03AM   1:49.48 /sbin/launchd
root             7878   0.0  0.0  2438348   1004 s001  R+    7:15PM   0:00.01 ps aux
root             7863   0.0  0.1  2496808   4456   ??  Ss    7:14PM   0:00.12 /usr/sbin/ocspd
root             7759   0.0  0.1  2471492   5308   ??  Ss    6:53PM   0:00.02 /System/Library/Frameworks/AudioToolbox.framework/XPCServices/com.apple.audio.SandboxHelper.xpc/Contents/MacOS/com.apple.audio.SandboxHelper
root             7758   0.0  0.1  2500348   4668   ??  Ss    6:53PM   0:00.25 /usr/sbin/systemsoundserverdTrixie           2478   3.9 12.8  5435488 537936   ??  U    Thu06PM 128:08.34 /Applications/Firefox.app/Contents/MacOS/firefox
```

Screenshot:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/1/local-root-processes.png">


#### 2)
```
Command: ps aux | grep Trixie

Output:

Trixie            531   2.0  1.2  2880792  50004   ??  S    Thu03AM  18:44.70 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=ppapi --channel=274.6.1052044262 --ppapi-flash-args --lang=en-US
Trixie            510   1.3  0.8  3579304  34140   ??  S    Thu03AM   9:25.28 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/VarationsServiceControl/Interval_30min/WebRTC-LocalIPPermissionCheck/Default/WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.2.964327342
Trixie            274   1.2  2.7  3392396 112612   ??  S    Thu03AM  34:41.12 /Applications/Google Chrome.app/Contents/MacOS/Google Chrome -psn_0_28679
Trixie            513   0.3  2.4  3653320 102748   ??  S    Thu03AM  32:41.27 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/WebRTC-LocalIPPermissionCheck/Default/WebRTC-PeerConnectionDTLS1.2/Enabled/ --extension-process --enable-webrtc-hw-h264-encoding --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.4.1367146913
Trixie           7760   0.0  0.3  2497996  12556   ??  Ss    6:53PM   0:00.08 /System/Library/Frameworks/AddressBook.framework/Versions/A/XPCServices/com.apple.AddressBook.InternetAccountsBridge.xpc/Contents/MacOS/com.apple.AddressBook.InternetAccountsBridge
Trixie           7757   0.0  0.1  2500892   4544   ??  S     6:53PM   0:00.06 /usr/libexec/swcd
Trixie           7756   0.0  0.1  2471492   2476   ??  S     6:53PM   0:00.02 /System/Library/PrivateFrameworks/ToneLibrary.framework/Versions/A/XPCServices/com.apple.tonelibraryd.xpc/Contents/MacOS/com.apple.tonelibraryd
Trixie           7752   0.0  0.2  2501040  10320   ??  S     6:53PM   0:00.11 /System/Library/PrivateFrameworks/CoreSpotlight.framework/Support/com.apple.spotlight.IndexAgent
Trixie           7751   0.0  0.2  2497628  10300   ??  S     6:53PM   0:00.40 /System/Library/PrivateFrameworks/CoreRecents.framework/Versions/A/Support/recentsd
Trixie           7750   0.0  0.3  2497160  11464   ??  Ss    6:53PM   0:00.06 /System/Library/Frameworks/AddressBook.framework/Versions/A/XPCServices/com.apple.AddressBook.InternetAccountsBridge.xpc/Contents/MacOS/com.apple.AddressBook.InternetAccountsBridge
Trixie           7742   0.0  0.5  2538524  21440   ??  U     6:53PM   0:01.63 /System/Library/PrivateFrameworks/IMDPersistence.framework/XPCServices/IMDPersistenceAgent.xpc/Contents/MacOS/IMDPersistenceAgent
Trixie           7739   0.0  0.1  2496796   3876   ??  S     6:53PM   0:00.04 /System/Library/PrivateFrameworks/CommunicationsFilter.framework/CMFSyncAgent.app/Contents/MacOS/CMFSyncAgent
Trixie           7735   0.0  0.2  2499084   6836   ??  Ss    6:53PM   0:00.39 /System/Library/PrivateFrameworks/IMFoundation.framework/XPCServices/IMRemoteURLConnectionAgent.xpc/Contents/MacOS/IMRemoteURLConnectionAgent
Trixie           7734   0.0  0.1  2497252   3152   ??  S     6:53PM   0:00.03 /System/Library/CoreServices/AirPort Base Station Agent.app/Contents/MacOS/AirPort Base Station Agent --launchd
Trixie           7701   0.0  0.3  2507796  13488   ??  S     6:53PM   0:00.88 /System/Library/Frameworks/AddressBook.framework/Versions/A/Helpers/AddressBookSourceSync.app/Contents/MacOS/AddressBookSourceSync
Trixie           7650   0.0  0.1  2497016   3188   ??  S    10:37PM   0:00.29 /System/Library/PrivateFrameworks/AOSKit.framework/Versions/A/XPCServices/com.apple.iCloudHelper.xpc/Contents/MacOS/com.apple.iCloudHelper
Trixie           7632   0.0  0.0  2501904   2080   ??  S    10:29PM   0:00.06 /System/Library/CoreServices/iconservicesagent
Trixie           7621   0.0  0.1  2500708   4328   ??  Ss   10:26PM   0:00.15 /System/Library/PrivateFrameworks/CloudDocsDaemon.framework/XPCServices/ContainerMetadataExtractor.xpc/Contents/MacOS/ContainerMetadataExtractor
Trixie           7620   0.0  0.0  2501564   1108   ??  S    10:26PM   0:00.15 /System/Library/Frameworks/InputMethodKit.framework/Versions/A/XPCServices/com.apple.InputMethodKit.TextReplacementService.xpc/Contents/MacOS/com.apple.InputMethodKit.TextReplacementService
Trixie           7618   0.0  0.1  2499820   2908   ??  S    10:26PM   0:00.08 /System/Library/Frameworks/CoreServices.framework/Frameworks/Metadata.framework/Versions/A/Support/mdworker -s mdworker -c MDSImporterWorker -m com.apple.mdworker.single
Trixie           7553   0.0  0.0  2524136   1572   ??  S     9:59PM   0:00.24 /System/Library/LoginPlugins/BezelServices.loginPlugin/Contents/Resources/BezelUI/BezelUIServer
Trixie           7529   0.0  0.1  2500844   3940   ??  S     9:50PM   0:00.23 /usr/libexec/pkd
Trixie           7522   0.0  0.0  2500616   1300   ??  U     9:49PM   0:00.14 /System/Library/CoreServices/ScopedBookmarkAgent
Trixie           7521   0.0  0.2  2525000  10328   ??  Ss    9:49PM   0:00.85 /System/Library/PrivateFrameworks/CommerceKit.framework/Versions/A/XPCServices/com.apple.CommerceKit.TransactionService.xpc/Contents/MacOS/com.apple.CommerceKit.TransactionService
Trixie           7518   0.0  0.3  2505928  10948   ??  Ss    9:49PM   0:02.13 /System/Library/PrivateFrameworks/CalendarAgent.framework/Versions/A/XPCServices/CalNCService.xpc/Contents/MacOS/CalNCService
Trixie           7505   0.0  0.1  2498856   2176   ??  S     9:46PM   0:00.30 /System/Library/CoreServices/mapspushd
Trixie           7503   0.0  0.7  2570796  28936   ??  S     9:46PM   0:01.53 /System/Library/PrivateFrameworks/CoreSuggestions.framework/Versions/A/Support/suggestd
Trixie           7498   0.0  0.1  2525264   3712   ??  S     9:44PM   0:00.25 /System/Library/CoreServices/CoreServicesUIAgent.app/Contents/MacOS/CoreServicesUIAgent
Trixie           7496   0.0  0.0  2471132   1628   ??  S     9:43PM   0:00.06 /System/Library/Frameworks/Security.framework/Versions/A/Resources/CloudKeychainProxy.bundle/Contents/MacOS/CloudKeychainProxy
Trixie           7495   0.0  0.0  2471024   1596   ??  S     9:43PM   0:00.05 /System/Library/Frameworks/Security.framework/Versions/A/Resources/IDSKeychainSyncingProxy.bundle/Contents/MacOS/IDSKeychainSyncingProxy
Trixie           7494   0.0  0.1  2498520   2116   ??  S     9:43PM   0:00.22 /usr/libexec/secd
Trixie           7493   0.0  0.1  2471600   2888   ??  S     9:43PM   0:00.92 /usr/sbin/cfprefsd agent
Trixie           7491   0.0  0.0  2497768   1096   ??  U     9:43PM   0:00.14 /usr/libexec/secinitd
Trixie           7490   0.0  0.0  2522784   1792   ??  S     9:43PM   0:00.18 /System/Library/CoreServices/AirPlayUIAgent.app/Contents/MacOS/AirPlayUIAgent --launchd
Trixie           7486   0.0  0.1  2500616   4228   ??  S     9:43PM   0:00.62 /usr/libexec/nsurlstoraged
Trixie           7485   0.0  0.1  2502540   5788   ??  S     9:43PM   0:00.48 /System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/Support/akd
Trixie           7481   0.0  0.4  2528876  18312   ??  S     9:43PM   0:04.48 /System/Library/Frameworks/Accounts.framework/Versions/A/Support/accountsd
Trixie           7480   0.0  0.0  2497204   1860   ??  U     9:43PM   0:00.27 /System/Library/Frameworks/AddressBook.framework/Versions/A/XPCServices/com.apple.AddressBook.ContactsAccountsService.xpc/Contents/MacOS/com.apple.AddressBook.ContactsAccountsService
Trixie           7479   0.0  0.1  2501504   3000   ??  S     9:43PM   0:00.19 /System/Library/PrivateFrameworks/TCC.framework/Resources/tccd
Trixie           7476   0.0  0.2  2519308  10216   ??  S     9:43PM   0:02.31 /System/Library/PrivateFrameworks/MessagesKit.framework/Resources/soagent.app/Contents/MacOS/soagent
Trixie           6999   0.0  1.5  3373388  63392   ??  S    Sat07PM   0:09.10 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.86.260605164
Trixie           6954   0.0  2.1  3733220  89440   ??  S    Sat06PM   6:06.07 /Applications/Spotify.app/Contents/Frameworks/Spotify Helper.app/Contents/MacOS/Spotify Helper --type=renderer --lang=en-US --lang=en-US --log-file=/Users/Trixie/Library/Logs/Spotify_debug.log --log-severity=disable --product-version=Spotify/1.0.23.90 --disable-extensions --disable-scroll-bounce --disable-spell-checking --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=6946.1.943068880
Trixie           6952   0.0  0.0  2474452    888   ??  S    Sat06PM   0:00.73 /Users/Trixie/Library/Application Support/Spotify/SpotifyWebHelper
Trixie           6947   0.0  0.1  2725880   3996   ??  S    Sat06PM   1:19.17 /Applications/Spotify.app/Contents/Frameworks/Spotify Helper.app/Contents/MacOS/Spotify Helper --type=gpu-process --channel=6946.0.453160856 --lang=en-US --log-file=/Users/Trixie/Library/Logs/Spotify_debug.log --log-severity=disable --product-version=Spotify/1.0.23.90 --supports-dual-gpus=false --gpu-driver-bug-workarounds=14,15,29,34,38,47,51,54,58,64 --gpu-vendor-id=0x8086 --gpu-device-id=0x0a26 --gpu-driver-vendor --gpu-driver-version --lang=en-US --log-file=/Users/Trixie/Library/Logs/Spotify_debug.log --log-severity=disable --product-version=Spotify/1.0.23.90
Trixie           6946   0.0  1.0  2983092  42872   ??  S    Sat06PM   4:51.94 /Applications/Spotify.app/Contents/MacOS/Spotify -psn_0_53261
Trixie           6895   0.0  0.2  2526132   9852   ??  S    Sat06PM   0:03.89 /System/Library/Frameworks/CoreServices.framework/Frameworks/Metadata.framework/Versions/A/Support/mdworker -s mdworker -c MDSImporterWorker -m com.apple.mdworker.shared
Trixie           6894   0.0  0.3  2523580  13068   ??  S    Sat06PM   0:02.78 /System/Library/Frameworks/CoreServices.framework/Frameworks/Metadata.framework/Versions/A/Support/mdworker -s mdworker -c MDSImporterWorker -m com.apple.mdworker.shared
Trixie           6892   0.0  0.2  2527976   6724   ??  S    Sat06PM   0:04.73 /System/Library/Frameworks/CoreServices.framework/Frameworks/Metadata.framework/Versions/A/Support/mdworker -s mdworker -c MDSImporterWorker -m com.apple.mdworker.shared
Trixie           6891   0.0  0.2  2523060   9172   ??  S    Sat06PM   0:02.12 /System/Library/Frameworks/CoreServices.framework/Frameworks/Metadata.framework/Versions/A/Support/mdworker -s mdworker -c MDSImporterWorker -m com.apple.mdworker.shared
Trixie           6788   0.0  0.7  3346496  28228   ??  S    Sat06PM   0:03.51 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.83.1244599800
Trixie           6783   0.0  0.0  2496708    252   ??  S    Sat06PM   0:00.03 /System/Library/PrivateFrameworks/HelpData.framework/Versions/A/Resources/helpd
Trixie           6757   0.0  1.6  3438944  66492   ??  S    Sat06PM   0:46.42 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --extension-process --enable-webrtc-hw-h264-encoding --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.82.179556921
Trixie           6756   0.0  0.8  3342820  33176   ??  S    Sat06PM   0:05.08 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.81.1184882156
Trixie           6755   0.0  0.7  3349600  28624   ??  S    Sat06PM   0:10.59 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.80.1586784652
Trixie           6736   0.0  0.3  3258544  11164   ??  S    Sat06PM   0:15.71 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=ppapi --channel=274.79.2087335637 --ppapi-flash-args --lang=en-US
Trixie           4340   0.0  0.0  2558684   1788   ??  Ss   Fri04PM   0:00.61 /Applications/Dropbox.app/Contents/PlugIns/garcon.appex/Contents/MacOS/garcon
Trixie           4325   0.0  0.0  2558684   1800   ??  Ss   Fri04PM   0:00.61 /Applications/Dropbox.app/Contents/PlugIns/garcon.appex/Contents/MacOS/garcon
Trixie           4314   0.0  0.0   412384     56   ??  S    Fri04PM   0:04.23 /Library/DropboxHelperTools/Dropbox_u501/dbfseventsd
Trixie           4297   0.0  0.8  3988076  31680   ??  S    Fri04PM   0:58.10 /Applications/Dropbox.app/Contents/MacOS/Dropbox /firstrunupdate 457
Trixie           3405   0.0  0.0  2502892   1780   ??  S    Thu11PM   0:01.61 /usr/libexec/nsurlsessiond
Trixie           3404   0.0  0.1  2527224   2260   ??  S    Thu11PM   0:00.97 /System/Library/PrivateFrameworks/Noticeboard.framework/Versions/A/Resources/nbagent.app/Contents/MacOS/nbagent
Trixie           3138   0.0  0.0  2471472    156   ??  S    Thu11PM   0:00.05 /System/Library/PrivateFrameworks/KerberosHelper/Helpers/DiskUnmountWatcher
Trixie           2925   0.0  0.0  2525076   1596   ??  S    Thu10PM   0:00.48 /System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/A/Resources/universalAccessAuthWarn.app/Contents/MacOS/universalAccessAuthWarn launchd -s
Trixie           2280   0.0  0.0  2501392    268   ??  S    Thu04PM   0:00.14 /System/Library/Frameworks/CoreServices.framework/Frameworks/Metadata.framework/Versions/A/Support/mdworker -s mdworker-sizing -c MDSSizingWorker -m com.apple.mdworker.sizing
Trixie           1812   0.0  0.2  2500644   8260   ??  S    Thu12PM   0:19.74 /System/Library/PrivateFrameworks/SyncedDefaults.framework/Support/syncdefaultsd
Trixie           1627   0.0  0.2  3771428   9284   ??  S    Thu12PM   2:29.42 /Applications/Preview.app/Contents/MacOS/Preview -psn_0_479349
Trixie           1345   0.0  0.0  2470948    152   ??  S    Thu11AM   0:00.02 /usr/libexec/ApplicationFirewall/Firewall
Trixie           1300   0.0  0.6  3528748  26852   ??  S    Thu11AM   0:53.85 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.34.1751363146
Trixie           1299   0.0  0.6  3477772  26220   ??  S    Thu11AM   0:32.79 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.33.1911293908
Trixie           1298   0.0  0.5  3462064  22804   ??  S    Thu11AM   0:26.21 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.32.1329876552
Trixie           1297   0.0  0.6  3472584  24476   ??  S    Thu11AM   0:27.72 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.31.1548880944
Trixie           1294   0.0  0.7  3471108  29152   ??  S    Thu11AM   0:28.99 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.30.951312704
Trixie           1285   0.0  0.5  3474144  22896   ??  S    Thu11AM   0:26.19 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.29.2129537139
Trixie           1283   0.0  4.7  3614408 197940   ??  S    Thu11AM   3:27.75 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.28.137140097
Trixie           1280   0.0  0.5  3476840  22408   ??  S    Thu11AM   0:15.92 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/*SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/*WebRTC-LocalIPPermissionCheck/Default/*WebRTC-PeerConnectionDTLS1.2/Enabled/ --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.27.1064248050
Trixie           1270   0.0  0.0  2471488    260   ??  S    Thu11AM   0:00.09 /usr/libexec/USBAgent
Trixie            598   0.0  0.0  2505176    128   ??  S    Thu03AM   0:00.46 /System/Library/Frameworks/ApplicationServices.framework/Frameworks/SpeechSynthesis.framework/Resources/com.apple.speech.speechsynthesisd
Trixie            545   0.0  0.0  2471284    328   ??  S    Thu03AM   0:01.71 /System/Library/Frameworks/CoreServices.framework/Frameworks/Metadata.framework/Versions/A/Support/mdflagwriter
Trixie            514   0.0  0.4  3314216  16900   ??  S    Thu03AM   0:12.02 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/*MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/WebRTC-LocalIPPermissionCheck/Default/WebRTC-PeerConnectionDTLS1.2/Enabled/ --extension-process --enable-webrtc-hw-h264-encoding --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.5.1855701234
Trixie            512   0.0  0.1  3283988   5700   ??  S    Thu03AM   0:02.16 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/*CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/*ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/*IntelligentSessionRestore/Enabled2/MacMemoryMechanism/Posix/*OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/*SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/*VarationsServiceControl/Interval_30min/WebRTC-LocalIPPermissionCheck/Default/WebRTC-PeerConnectionDTLS1.2/Enabled/ --extension-process --enable-webrtc-hw-h264-encoding --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.3.2065823024
Trixie            503   0.0  0.0  2526916   1964   ??  S    Thu03AM   0:02.60 /System/Library/Image Capture/Support/Image Capture Extension.app/Contents/MacOS/Image Capture Extension
Trixie            501   0.0  0.0  2525112   1492   ??  S    Thu03AM   0:00.82 /System/Library/PrivateFrameworks/CommerceKit.framework/Resources/LaterAgent.app/Contents/MacOS/LaterAgent
Trixie            492   0.0  0.0  2496652    104   ??  S    Thu03AM   0:00.14 /System/Library/PrivateFrameworks/CommerceKit.framework/Versions/A/Resources/storelegacy
Trixie            484   0.0  0.2  3296872   9696   ??  S    Thu03AM   0:03.79 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=renderer --lang=en-US --force-fieldtrials=AffiliationBasedMatching/EnabledThroughFieldTrial/AppBannerTriggering/Aggressive/AutofillProfileOrderByFrecency/Enabled/*AutomaticTabDiscarding/Enabled_Once_5/CaptivePortalInterstitial/Enabled/ChildAccountDetection/Disabled/*ChromeSuggestions/Default/*ClientSideDetectionModel/Model0/CrossDevicePromo/14DaySingleProfile/*ExtensionActionRedesign/Default/ExtensionDeveloperModeWarning/Default/*ExtensionInstallVerification/Enforce/*GFE/Default/InstanceID/Enabled/IntelligentSessionRestore/Enabled2/MacMemoryMechanism/Posix/OmniboxBundledExperimentV1/Postperiod_AnswersInSuggest_A2/PasswordBranding/Disabled/*PasswordGeneration/Disabled/*PasswordManagerSettingsMigration/Disable/*QUIC/EnabledNoId/ReportCertificateErrors/ShowAndPossiblySend/*ResourcePriorities/Disabled/SHA1IdentityUIWarning/Enabled/SHA1ToolbarUIJanuary2016/Warning/SHA1ToolbarUIJanuary2017/Error/*SafeBrowsingIncidentReportingService/Default/SafeBrowsingUnverifiedDownloads/DisableByParameterMostSbTypes2/SafeBrowsingUpdateFrequency/Default/SlimmingPaint/EnableSlimmingPaint/SpdyEnableDependencies/Enable/*UMA-Dynamic-Uniformity-Trial/Group3/*UMA-Population-Restrict/normal/*UMA-Uniformity-Trial-100-Percent/group_01/*UMA-Uniformity-Trial-20-Percent/default/*UMA-Uniformity-Trial-50-Percent/default/*UseDelayAgnosticAEC/DefaultEnabled/VarationsServiceControl/Interval_30min/WebRTC-LocalIPPermissionCheck/Default/WebRTC-PeerConnectionDTLS1.2/Enabled/ --extension-process --enable-webrtc-hw-h264-encoding --enable-offline-auto-reload --enable-offline-auto-reload-visible-only --num-raster-threads=2 --enable-zero-copy --content-image-texture-target=3553,3553,3553,3553,3553,34037,3553,3553,3553,3553,34037,3553,34037,34037 --video-image-texture-target=34037 --channel=274.1.182414723
Trixie            475   0.0  0.3  2635532  11640   ??  S    Thu03AM   0:31.21 /System/Library/Services/AppleSpell.service/Contents/MacOS/AppleSpell -psn_0_167977
Trixie            470   0.0  0.0  2499320    144   ??  S    Thu03AM   0:00.24 /System/Library/PrivateFrameworks/CommerceKit.framework/Versions/A/Resources/storedownloadd
Trixie            469   0.0  0.0  2499084   1256   ??  S    Thu03AM   0:01.49 /System/Library/PrivateFrameworks/CommerceKit.framework/Versions/A/Resources/storeinappd
Trixie            465   0.0  0.3  2643268  12600   ??  S    Thu03AM   0:49.34 /Applications/DrCleaner.app/Contents/MacOS/DrCleaner
Trixie            464   0.0  0.2  2553984   6460   ??  S    Thu03AM   0:52.85 /Applications/Memory Clean.app/Contents/MacOS/Memory Clean
Trixie            463   0.0  0.0  2468124    336   ??  Ss   Thu03AM   0:02.43 postgres: stats collector process       
Trixie            462   0.0  0.0  2612980    928   ??  Ss   Thu03AM   0:00.97 postgres: autovacuum launcher process       
Trixie            461   0.0  0.0  2612980     88   ??  Ss   Thu03AM   0:00.89 postgres: wal writer process       
Trixie            460   0.0  0.0  2612980    140   ??  Ss   Thu03AM   0:00.95 postgres: writer process       
Trixie            459   0.0  0.0  2612980    140   ??  Ss   Thu03AM   0:00.05 postgres: checkpointer process       
Trixie            456   0.0  0.0  2503324    208   ??  S    Thu03AM   0:00.31 /Applications/iTunes.app/Contents/MacOS/iTunesHelper.app/Contents/MacOS/iTunesHelper
Trixie            449   0.0  0.1  2502764   3428   ??  S    Thu03AM   0:02.45 /System/Library/CoreServices/diagnostics_agent
Trixie            448   0.0  0.0  2523920   1888   ??  S    Thu03AM   0:01.25 /System/Library/CoreServices/WiFiAgent.app/Contents/MacOS/WiFiAgent
Trixie            445   0.0  0.0  2496780   1564   ??  S    Thu03AM   0:00.29 /System/Library/CoreServices/cloudpaird
Trixie            442   0.0  0.0  2615028    280   ??  S    Thu03AM   0:01.00 /usr/local/opt/postgresql/bin/postgres -D /usr/local/var/postgres -r /usr/local/var/postgres/server.log
Trixie            439   0.0  0.0  2497308    444   ??  S    Thu03AM   0:00.46 /System/Library/Image Capture/Support/icdd
Trixie            437   0.0  0.4  2580900  15120   ??  S    Thu03AM   0:19.19 /System/Library/CoreServices/NotificationCenter.app/Contents/MacOS/NotificationCenter
Trixie            434   0.0  0.0  2522744   1384   ??  S    Thu03AM   0:00.78 /System/Library/CoreServices/Keychain Circle Notification.app/Contents/MacOS/Keychain Circle Notification
Trixie            432   0.0  0.0  2496756    416   ??  S    Thu03AM   0:00.29 /System/Library/CoreServices/SocialPushAgent.app/Contents/MacOS/SocialPushAgent
Trixie            415   0.0  0.1  2516328   5240   ??  S    Thu03AM   0:05.44 /Applications/Sublime Text.app/Contents/MacOS/plugin_host 287
Trixie            401   0.0  0.0  2463080    880 s001  S    Thu03AM   0:00.18 -bash
Trixie            390   0.0  0.0  2463080     36 s000  S+   Thu03AM   0:00.42 -bash
Trixie            382   0.0  0.5  2823116  21572   ??  S    Thu03AM   5:41.39 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Helper.app/Contents/MacOS/Google Chrome Helper --type=gpu-process --channel=274.0.1294789169 --supports-dual-gpus=false --gpu-driver-bug-workarounds=15,16,30,35,39,48,52,55,59,65 --gpu-vendor-id=0x8086 --gpu-device-id=0x0a26 --gpu-driver-vendor --gpu-driver-version
Trixie            374   0.0  0.1  2502320   2656   ??  S    Thu03AM   0:00.91 /System/Library/PrivateFrameworks/DataDetectorsCore.framework/Versions/A/XPCServices/DataDetectorsDynamicData.xpc/Contents/MacOS/DataDetectorsDynamicData
Trixie            364   0.0  0.1  2499316   2568   ??  S    Thu03AM   0:03.82 /System/Library/PrivateFrameworks/GeoServices.framework/Versions/A/XPCServices/com.apple.geod.xpc/Contents/MacOS/com.apple.geod
Trixie            352   0.0  0.0  2506112   2008   ??  S    Thu03AM   0:09.50 /System/Library/PrivateFrameworks/ParsecUI.framework/Versions/A/Support/SpotlightNetHelper.app/Contents/MacOS/SpotlightNetHelper
Trixie            351   0.0  0.0  2472256    448   ??  S    Thu03AM   0:00.11 /Applications/Google Chrome.app/Contents/Versions/48.0.2564.109/Google Chrome Framework.framework/Helpers/crashpad_handler --database=/Users/Trixie/Library/Application Support/Google/Chrome/Crashpad --url=https://clients2.google.com/cr/report --annotation=plat=OS X --annotation=prod=Chrome_Mac --annotation=ver=48.0.2564.109 --handshake-fd=8
Trixie            347   0.0  0.1  2503844   6284   ??  S    Thu03AM   0:05.93 /System/Library/PrivateFrameworks/IMCore.framework/imagent.app/Contents/MacOS/imagent
Trixie            340   0.0  0.1  2523952   3264   ??  Ss   Thu03AM   0:01.83 /System/Library/CoreServices/Dock.app/Contents/XPCServices/com.apple.dock.extra.xpc/Contents/MacOS/com.apple.dock.extra
Trixie            338   0.0  0.1  2497112   2224   ??  S    Thu03AM   0:02.23 /System/Library/PrivateFrameworks/UserActivity.framework/Agents/useractivityd
Trixie            336   0.0  0.0  2505172   1180   ??  Ss   Thu03AM   0:00.78 /System/Library/PrivateFrameworks/CoreWLANKit.framework/Versions/A/XPCServices/WiFiProxy.xpc/Contents/MacOS/WiFiProxy
Trixie            334   0.0  0.0  2503696   1496   ??  S    Thu03AM   0:09.22 /System/Library/PrivateFrameworks/CommerceKit.framework/Versions/A/Resources/storeassetd
Trixie            329   0.0  0.1  2507984   5488   ??  S    Thu03AM   0:02.39 /usr/libexec/sharingd
Trixie            326   0.0  0.1  2498492   3932   ??  S    Thu03AM   0:07.75 /usr/sbin/usernoted
Trixie            323   0.0  0.0  2505364   1528   ??  S    Thu03AM   0:03.72 /System/Library/PrivateFrameworks/CommerceKit.framework/Versions/A/Resources/storeaccountd
Trixie            322   0.0  0.1  2531568   5580   ??  S    Thu03AM   0:15.07 /System/Library/Frameworks/ApplicationServices.framework/Frameworks/ATS.framework/Support/fontd
Trixie            321   0.0  0.3  4222644  11084   ??  S    Thu03AM   0:26.93 /System/Library/CoreServices/Spotlight.app/Contents/MacOS/Spotlight
Trixie            319   0.0  0.0  2462480     32   ??  S    Thu03AM   0:00.02 /usr/sbin/pboard
Trixie            317   0.0  0.2  2503556   8796   ??  S    Thu03AM   0:08.73 /System/Library/PrivateFrameworks/CloudDocsDaemon.framework/Versions/A/Support/bird
Trixie            314   0.0  0.0  2496768    212   ??  S    Thu03AM   0:00.22 /System/Library/PrivateFrameworks/AskPermission.framework/Versions/A/Resources/askpermissiond
Trixie            304   0.0  0.7  2778360  27556   ??  S    Thu03AM   1:55.13 /System/Library/CoreServices/Finder.app/Contents/MacOS/Finder
Trixie            303   0.0  0.3  2539796  11524   ??  S    Thu03AM   0:21.89 /System/Library/CoreServices/SystemUIServer.app/Contents/MacOS/SystemUIServer
Trixie            302   0.0  0.2  2581500   9244   ??  S    Thu03AM   0:25.26 /System/Library/CoreServices/Dock.app/Contents/MacOS/Dock
Trixie            289   0.0  0.4  2519540  17200   ??  S    Thu03AM   1:54.49 /System/Library/PrivateFrameworks/CalendarAgent.framework/Executables/CalendarAgent
Trixie            287   0.0  0.9  2672500  39072   ??  S    Thu03AM   1:04.61 /Applications/Sublime Text.app/Contents/MacOS/Sublime Text -psn_0_49164
Trixie            285   0.0  0.2  2506132   9596   ??  S    Thu03AM   0:06.42 /System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/Contents/MacOS/identityservicesd
Trixie            283   0.0  1.3  3814348  53252   ??  S    Thu03AM   2:44.76 /Applications/Mail.app/Contents/MacOS/Mail -psn_0_40970
Trixie            282   0.0  0.8  2688880  33484   ??  S    Thu03AM   0:52.25 /Applications/Utilities/Terminal.app/Contents/MacOS/Terminal -psn_0_36873
Trixie            279   0.0  1.0  3931240  42028   ??  S    Thu03AM   0:41.63 /Applications/Messages.app/Contents/MacOS/Messages -psn_0_32776
Trixie            277   0.0  0.1  2499168   2560   ??  S    Thu03AM   0:01.80 /System/Library/CoreServices/sharedfilelistd
Trixie            273   0.0  0.1  2502408   4048   ??  S    Thu03AM   0:03.99 /usr/libexec/lsd
Trixie            272   0.0  0.1  2530276   5468   ??  S    Thu03AM   0:08.18 /System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter
Trixie            270   0.0  0.1  2518164   2812   ??  S    Thu03AM   0:03.33 /usr/sbin/universalaccessd launchd -s
Trixie            269   0.0  0.1  2470804   2996   ??  S    Thu03AM   0:18.91 /usr/sbin/distnoted agent
Trixie            267   0.0  0.1  2502872   3240   ??  S    Thu03AM   0:06.90 /usr/libexec/UserEventAgent (Aqua)
Trixie            105   0.0  0.3  2552352  13140   ??  Ss   Thu03AM   0:26.50 /System/Library/CoreServices/loginwindow.app/Contents/MacOS/loginwindow console
Trixie           7889   0.0  0.0  2444052    780 s001  S+    7:17PM   0:00.01 grep Trixie
Trixie           7864   0.0  0.5  2515980  19824   ??  Ss    7:14PM   0:00.25 /System/Library/Frameworks/QuickLook.framework/Versions/A/Resources/quicklookd.app/Contents/XPCServices/QuickLookSatellite.xpc/Contents/MacOS/QuickLookSatellite
Trixie           7862   0.0  0.4  3018028  15236   ??  S     7:14PM   0:00.22 /System/Library/Frameworks/QuickLook.framework/Resources/quicklookd.app/Contents/MacOS/quicklookd
Trixie           7763   0.0  0.3  3550224  13704   ??  S     6:53PM   0:00.14 /System/Library/PrivateFrameworks/CoreSuggestions.framework/Versions/A/Support/reversetemplated
```

Screenshot:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/1/local-user-processes.png">

#### 3) 
```
kernel_task is using the most real memory: 487 MB
Firefox is using the most virtual memory: 975 MB
```

Screenshot:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/1/activity-monitor.png">

#### 4)
```
Command: ps aux | sort 
(Eye-balled the processes that are not "root" and "troque")

daemon
ikhizani
jyen2
message+
mysql
ntop
ntp
postfix
sshd
syslog
www-data 
```

Screenshots:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/1/ssh-root-processes-1.png">
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/1/ssh-root-processes-2.png">


### I/O Gymnastics:

#### 1)
```
Command: ssh -L 55555:my.cs.lmu.edu:22 troque@my.cs.lmu.edu
```

Screenshots:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/ssh-tunneling.png">

Localhost:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/ssh-tunneling-localhost.png">


#### 2)
```
Command: screen ping google.com
```

Screenshots:

Screen Ping BEFORE:
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/screen-ping-before.png">

Screen Ping DURING:
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/screen-ping.png">

Screen Ping AFTER: <br>
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/screen-ping-after.png">



#### 3)
~/Pictures is the directory that uses the most disk space: 8.9 GB

```
Command: du -sh ~/*
```

Screenshots:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/du-sh-regex.png">

#### 4)
Using one of the Mac computers in the Keck Lab:

Screenshots:

```
Command: vi whateva.txt
```
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/txt-file.png">
```
Command: ls -i
```
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/ls-root-1.png">
```
Command: mv whateva.txt Desktop && ls -i
```
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/ls-desktop.png">
```
Command: cd Desktop && mv whateva.txt /tmp && ls -i
```
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/ls-tmp.png">
```
Command: cd /tmp && mv whateva.txt ~ && ls -i
```
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/ls-root-2.png">
```
Command to filter: ls -i | grep whateva.txt
```
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/ls-grep-command.png">

#### 5)
```
Command: diskutil list
```

Screenshot:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/2/storage-drives.png">

### CSI:OS:

#### Mac OSX:

Pre OS software:

Gives the user the option of which preloaded OS they wish to run before any OS is ran.
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/CSIOS/PreOSOSX.png">

Kernel file:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/CSIOS/KernelFileOSX.png">

Startup Scripts:

/System/Library/LaunchAgents/
```
com.apple.AOSHeartbeat.plist
com.apple.AOSPushRelay.plist
com.apple.AddressBook.AssistantService.plist
com.apple.AddressBook.SourceSync.plist
com.apple.AddressBook.abd.plist
com.apple.AirPlayUIAgent.plist
com.apple.AirPortBaseStationAgent.plist
com.apple.AppleGraphicsWarning.plist
com.apple.AskPermissionUI.plist
com.apple.AssetCacheLocatorService.plist
com.apple.AssistiveControl.plist
com.apple.BezelUI.plist
com.apple.CalendarAgent.plist
com.apple.CallHistoryPluginHelper.plist
com.apple.CallHistorySyncHelper.plist
com.apple.CommCenter-osx.plist
com.apple.ContainerRepairAgent.plist
com.apple.CoreAuthentication.daemon.plist
com.apple.CoreLocationAgent.plist
com.apple.CoreRAIDAgent.plist
com.apple.DiagnosticReportCleanup.plist
com.apple.DictationIM.plist
com.apple.DiskArbitrationAgent.plist
com.apple.Dock.plist
com.apple.EscrowSecurityAlert.plist
com.apple.FTCleanup.plist
com.apple.FileStatsAgent.plist
com.apple.FileSyncAgent.PHD.plist
com.apple.FilesystemUI.plist
com.apple.Finder.plist
com.apple.FolderActionsDispatcher.plist
com.apple.FollowUpUI.plist
com.apple.FontRegistryUIAgent.plist
com.apple.FontValidator.plist
com.apple.FontValidatorConduit.plist
com.apple.FontWorker.plist
com.apple.IMLoggingAgent.plist
com.apple.MRTa.plist
com.apple.ManagedClientAgent.agent.plist
com.apple.ManagedClientAgent.enrollagent.plist
com.apple.Maps.pushdaemon.plist
com.apple.NetworkDiagnostics.plist
com.apple.PCIESlotCheck.plist
com.apple.PackageKit.InstallStatus.plist
com.apple.PhotoLibraryMigrationUtility.XPC.plist
com.apple.PubSub.Agent.plist
com.apple.RemoteDesktop.plist
com.apple.ReportCrash.Self.plist
com.apple.ReportCrash.plist
com.apple.ReportGPURestart.plist
com.apple.ReportPanic.plist
com.apple.SSInvitationAgent.plist
com.apple.Safari.SafeBrowsing.Service.plist
com.apple.SafariCloudHistoryPushAgent.plist
com.apple.SafariNotificationAgent.plist
com.apple.SafariPlugInUpdateNotifier.plist
com.apple.ScreenReaderUIServer.plist
com.apple.SocialPushAgent.plist
com.apple.Spotlight.plist
com.apple.SystemUIServer.plist
com.apple.TMHelperAgent.SetupOffer.plist
com.apple.TMHelperAgent.plist
com.apple.TrustEvaluationAgent.plist
com.apple.USBAgent.plist
com.apple.UserEventAgent-Aqua.plist
com.apple.UserEventAgent-LoginWindow.plist
com.apple.UserNotificationCenterAgent-LoginWindow.plist
com.apple.UserNotificationCenterAgent.plist
com.apple.VoiceOver.plist
com.apple.WebKit.PluginAgent.plist
com.apple.ZoomWindow.plist
com.apple.accountsd.plist
com.apple.akd.plist
com.apple.alf.useragent.plist
com.apple.aos.migrate.plist
com.apple.appleseed.seedusaged.plist
com.apple.appsleepd.plist
com.apple.appstoreupdateagent.plist
com.apple.apsctl.plist
com.apple.askpermissiond.plist
com.apple.assistant_service.plist
com.apple.assistantd.plist
com.apple.bird.plist
com.apple.bluetoothUIServer.plist
com.apple.btsa.plist
com.apple.cdpd.plist
com.apple.cfnetwork.AuthBrokerAgent.plist
com.apple.cfnetwork.cfnetworkagent.plist
com.apple.cfprefsd.xpc.agent.plist
com.apple.cloudd.plist
com.apple.cloudfamilyrestrictionsd-mac.plist
com.apple.cloudpaird.plist
com.apple.cloudphotosd.plist
com.apple.cmfsyncagent.plist
com.apple.coredata.externalrecordswriter.plist
com.apple.coreservices.appleid.authentication.plist
com.apple.coreservices.lsactivity.plist
com.apple.coreservices.sharedfilelistd.plist
com.apple.coreservices.uiagent.plist
com.apple.csuseragent.plist
com.apple.ctkd.plist
com.apple.cvmsCompAgent3600_i386.plist
com.apple.cvmsCompAgent3600_i386_1.plist
com.apple.cvmsCompAgent3600_x86_64.plist
com.apple.cvmsCompAgent3600_x86_64_1.plist
com.apple.cvmsCompAgentLegacy_i386.plist
com.apple.cvmsCompAgentLegacy_i386_1.plist
com.apple.cvmsCompAgentLegacy_x86_64.plist
com.apple.cvmsCompAgentLegacy_x86_64_1.plist
com.apple.cvmsCompAgent_i386.plist
com.apple.cvmsCompAgent_i386_1.plist
com.apple.cvmsCompAgent_x86_64.plist
com.apple.cvmsCompAgent_x86_64_1.plist
com.apple.diagnostics_agent.plist
com.apple.distnoted.xpc.agent.plist
com.apple.dt.CommandLineTools.installondemand.plist
com.apple.familycircled.plist
com.apple.familycontrols.useragent.plist
com.apple.familynotificationd.plist
com.apple.findmymacmessenger.plist
com.apple.followupd.plist
com.apple.fontd.useragent.plist
com.apple.gamed.plist
com.apple.helpd.plist
com.apple.iCloudUserNotifications.plist
com.apple.icdd.plist
com.apple.icloud.findmydeviced.findmydevice-user-agent.plist
com.apple.icloud.fmfd.plist
com.apple.iconservices.iconservicesagent.plist
com.apple.identityservicesd.plist
com.apple.idsremoteurlconnectionagent.plist
com.apple.imagent.plist
com.apple.imavagent.plist
com.apple.imklaunchagent.plist
com.apple.imtransferagent.plist
com.apple.installandsetup.migrationhelper.user.plist
com.apple.installd.user.plist
com.apple.isst.plist
com.apple.java.InstallOnDemand.plist
com.apple.java.updateSharing.plist
com.apple.lateragent.plist
com.apple.locationmenu.plist
com.apple.lsd.plist
com.apple.maspushagent.plist
com.apple.mbbackgrounduseragent.plist
com.apple.mbfloagent.plist
com.apple.mbuseragent.plist
com.apple.mdmclient.agent.plist
com.apple.mdworker.32bit.plist
com.apple.mdworker.bundles.plist
com.apple.mdworker.isolation.plist
com.apple.mdworker.lsb.plist
com.apple.mdworker.mail.plist
com.apple.mdworker.shared.plist
com.apple.mdworker.single.plist
com.apple.mdworker.sizing.plist
com.apple.metadata.SpotlightNetHelper.plist
com.apple.metadata.mdbulkimport.plist
com.apple.metadata.mdflagwriter.plist
com.apple.metadata.mdwrite.plist
com.apple.midiserver.plist
com.apple.navd.plist
com.apple.neagent.plist
com.apple.netauth.user.auth.plist
com.apple.netauth.user.gui.plist
com.apple.noticeboard.agent.plist
com.apple.notificationcenterui.plist
com.apple.nsurlsessiond.plist
com.apple.nsurlstoraged.plist
com.apple.parentalcontrols.check.plist
com.apple.pboard.plist
com.apple.pbs.plist
com.apple.photolibraryd.plist
com.apple.pictd.plist
com.apple.pluginkit.pkd.plist
com.apple.pluginkit.pkreporter.plist
com.apple.powerchime.plist
com.apple.printtool.agent.plist
com.apple.printuitool.agent.plist
com.apple.quicklook.32bit.plist
com.apple.quicklook.config.plist
com.apple.quicklook.plist
com.apple.quicklook.ui.helper.plist
com.apple.rcd.plist
com.apple.recentsd.plist
com.apple.reversetemplated.plist
com.apple.rtcreportingd.plist
com.apple.safaridavclient.plist
com.apple.scopedbookmarkagent.xpc.plist
com.apple.screensharing.MessagesAgent.plist
com.apple.screensharing.agent.plist
com.apple.scrod.plist
com.apple.secd.plist
com.apple.secinitd.plist
com.apple.security.DiskUnmountWatcher.plist
com.apple.security.agent.plist
com.apple.security.cloudkeychainproxy.plist
com.apple.security.idskeychainsyncingproxy.plist
com.apple.security.keychain-circle-notification.plist
com.apple.sharingd.plist
com.apple.soagent.plist
com.apple.softwareupdate_notify_agent.plist
com.apple.speech.speechdatainstallerd.plist
com.apple.speech.speechsynthesisd.plist
com.apple.speech.synthesisserver.plist
com.apple.spindump_agent.plist
com.apple.spotlight.IndexAgent.plist
com.apple.storeaccountd.plist
com.apple.storeassetd.plist
com.apple.storedownloadd.plist
com.apple.storeinappd.plist
com.apple.storelegacy.plist
com.apple.storeuid.plist
com.apple.suggestd.plist
com.apple.swcd.plist
com.apple.syncdefaultsd.plist
com.apple.syncservices.SyncServer.plist
com.apple.syncservices.uihandler.plist
com.apple.systemprofiler.plist
com.apple.talagent.plist
com.apple.tccd.plist
com.apple.telephonyutilities.callservicesd.plist
com.apple.thermaltrap.plist
com.apple.tiswitcher.plist
com.apple.trustd.agent.plist
com.apple.universalaccessAuthWarn.plist
com.apple.universalaccesscontrol.plist
com.apple.universalaccessd.plist
com.apple.unmountassistant.useragent.plist
com.apple.usernoted.plist
com.apple.warmd_agent.plist
com.apple.webinspectord.plist
com.apple.wifi.WiFiAgent.plist
com.apple.xpc.loginitemregisterd.plist
com.apple.xpc.otherbsd.plist
org.openbsd.ssh-agent.plist
```

/System/Library/LaunchDameons
```
bootps.plist
com.apple.AirPlayXPCHelper.plist
com.apple.AppleFileServer.plist
com.apple.AssetCacheLocatorService.plist
com.apple.CommCenterRootHelper.plist
com.apple.CoreRAID.plist
com.apple.CrashReporterSupportHelper.plist
com.apple.DesktopServicesHelper.plist
com.apple.DumpGPURestart.plist
com.apple.DumpPanic.plist
com.apple.FileCoordination.plist
com.apple.FileSyncAgent.sshd.plist
com.apple.FontWorker.plist
com.apple.GSSCred.plist
com.apple.GameController.gamecontrollerd.plist
com.apple.IFCStart.plist
com.apple.IOAccelMemoryInfoCollector.plist
com.apple.IOBluetoothUSBDFU.plist
com.apple.Kerberos.digest-service.plist
com.apple.Kerberos.kadmind.plist
com.apple.Kerberos.kcm.plist
com.apple.Kerberos.kdc.plist
com.apple.Kerberos.kpasswdd.plist
com.apple.KernelEventAgent.plist
com.apple.MRTd.plist
com.apple.ManagedClient.cloudconfigurationd.plist
com.apple.ManagedClient.enroll.plist
com.apple.ManagedClient.plist
com.apple.ManagedClient.startup.plist
com.apple.MobileFileIntegrity.plist
com.apple.NetBootClientStatus.plist
com.apple.NetworkDiagnostics.plist
com.apple.NetworkLinkConditioner.plist
com.apple.NetworkSharing.plist
com.apple.ODSAgent.plist
com.apple.PCIELaneConfigTool.plist
com.apple.PasswordService.plist
com.apple.RFBEventHelper.plist
com.apple.RemoteDesktop.PrivilegeProxy.plist
com.apple.ReportCrash.Root.plist
com.apple.ReportPanicService.plist
com.apple.SCHelper.plist
com.apple.SubmitDiagInfo.plist
com.apple.TMCacheDelete.plist
com.apple.TrustEvaluationAgent.system.plist
com.apple.UserEventAgent-System.plist
com.apple.UserNotificationCenter.plist
com.apple.WindowServer.plist
com.apple.WirelessRadioManagerd-osx.plist
com.apple.afpfs_afpLoad.plist
com.apple.afpfs_checkafp.plist
com.apple.airplaydiagnostics.server.mac.plist
com.apple.airport.wps.plist
com.apple.airportd.plist
com.apple.akd.plist
com.apple.alf.agent.plist
com.apple.appleseed.fbahelperd.plist
com.apple.applessdstatistics.plist
com.apple.apsd.plist
com.apple.aslmanager.plist
com.apple.atrun.plist
com.apple.audio.coreaudiod.plist
com.apple.audio.systemsoundserverd.plist
com.apple.auditd.plist
com.apple.autofsd.plist
com.apple.automountd.plist
com.apple.avbdeviced.plist
com.apple.awacsd.plist
com.apple.awdd.plist
com.apple.backupd-auto.plist
com.apple.backupd.plist
com.apple.blued.plist
com.apple.bluetoothReporter.plist
com.apple.bluetoothaudiod.plist
com.apple.bnepd.plist
com.apple.bsd.dirhelper.plist
com.apple.cache_delete.plist
com.apple.cfprefsd.xpc.daemon.plist
com.apple.cloudfamilyrestrictionsd-mac.plist
com.apple.cmio.AVCAssistant.plist
com.apple.cmio.AppleCameraAssistant.plist
com.apple.cmio.IIDCVideoAssistant.plist
com.apple.cmio.VDCAssistant.plist
com.apple.cmio.iOSScreenCaptureAssistant.plist
com.apple.colorsyncd.plist
com.apple.comsat.plist
com.apple.configd.plist
com.apple.configureLocalKDC.plist
com.apple.corecaptured.plist
com.apple.coreduetd.osx.plist
com.apple.coreservices.appleevents.plist
com.apple.coreservices.appleid.passwordcheck.plist
com.apple.coreservices.launchservicesd.plist
com.apple.coreservices.sharedfilelistd.plist
com.apple.coreservicesd.plist
com.apple.corestorage.corestoraged.plist
com.apple.corestorage.corestoragehelperd.plist
com.apple.coresymbolicationd.plist
com.apple.csrutil.report.plist
com.apple.ctkd.plist
com.apple.cvmsServ.plist
com.apple.diagnostic.uuidpathd.plist
com.apple.diagnosticd.plist
com.apple.diskarbitrationd.plist
com.apple.diskmanagementd.plist
com.apple.diskmanagementstartup.plist
com.apple.displaypolicyd.plist
com.apple.distnoted.xpc.daemon.plist
com.apple.dnsextd.plist
com.apple.dpaudiothru.plist
com.apple.dpd.plist
com.apple.dspluginhelperd.plist
com.apple.dvdplayback.setregion.plist
com.apple.dynamic_pager.plist
com.apple.eapolcfg_auth.plist
com.apple.efax.plist
com.apple.efilogin-helper.plist
com.apple.emlog.plist
com.apple.emond.aslmanager.plist
com.apple.emond.plist
com.apple.eppc.plist
com.apple.familycontrols.plist
com.apple.findmymac.plist
com.apple.findmymacmessenger.plist
com.apple.firmwaresyncd.plist
com.apple.fontd.plist
com.apple.fontmover.plist
com.apple.fseventsd.plist
com.apple.ftp-proxy.plist
com.apple.getty.plist
com.apple.gkreport.plist
com.apple.gssd.plist
com.apple.hdiejectd.plist
com.apple.hidd.plist
com.apple.hidfud.plist
com.apple.icloud.findmydeviced.plist
com.apple.iconservices.iconservicesagent.plist
com.apple.iconservices.iconservicesd.plist
com.apple.ifdreader.plist
com.apple.installandsetup.systemmigrationd.plist
com.apple.installd.plist
com.apple.kcproxy.plist
com.apple.kdumpd.plist
com.apple.kextd.plist
com.apple.kuncd.plist
com.apple.locate.plist
com.apple.locationd.plist
com.apple.lockd.plist
com.apple.logd.plist
com.apple.logind.plist
com.apple.loginwindow.LFVTracer.plist
com.apple.loginwindow.plist
com.apple.logkextloadsd.plist
com.apple.lsd.plist
com.apple.mDNSResponder.plist
com.apple.mDNSResponderHelper.plist
com.apple.mbsystemadministration.plist
com.apple.mbusertrampoline.plist
com.apple.mdmclient.daemon.plist
com.apple.mdmclient.daemon.runatboot.plist
com.apple.metadata.mds.index.plist
com.apple.metadata.mds.plist
com.apple.metadata.mds.scan.plist
com.apple.metadata.mds.spindump.plist
com.apple.msrpc.echosvc.plist
com.apple.msrpc.lsarpc.plist
com.apple.msrpc.mdssvc.plist
com.apple.msrpc.netlogon.plist
com.apple.msrpc.srvsvc.plist
com.apple.msrpc.wkssvc.plist
com.apple.mtmd.plist
com.apple.mtmfs.plist
com.apple.nehelper.plist
com.apple.nesessionmanager.plist
com.apple.netauth.sys.auth.plist
com.apple.netauth.sys.gui.plist
com.apple.netbiosd.plist
com.apple.networkd.plist
com.apple.networkd_privileged.plist
com.apple.newsyslog.plist
com.apple.nfsconf.plist
com.apple.nfsd.plist
com.apple.nis.ypbind.plist
com.apple.noticeboard.state.plist
com.apple.notifyd.plist
com.apple.nsurlsessiond.plist
com.apple.nsurlstoraged.plist
com.apple.ocspd.plist
com.apple.odproxyd.plist
com.apple.opendirectoryd.plist
com.apple.periodic-daily.plist
com.apple.periodic-monthly.plist
com.apple.periodic-weekly.plist
com.apple.pfctl.plist
com.apple.pfd.plist
com.apple.platform.ptmd.plist
com.apple.powerd.plist
com.apple.powerd.swd.plist
com.apple.preferences.timezone.admintool.plist
com.apple.preferences.timezone.auto.plist
com.apple.printtool.daemon.plist
com.apple.racoon.plist
com.apple.remotepairtool.plist
com.apple.revisiond.plist
com.apple.rootless.init.plist
com.apple.rpcbind.plist
com.apple.sandboxd.plist
com.apple.screensharing.plist
com.apple.scsid.plist
com.apple.secinitd.plist
com.apple.security.FDERecoveryAgent.plist
com.apple.security.agent.login.plist
com.apple.security.authhost.plist
com.apple.security.syspolicy.plist
com.apple.securityd.plist
com.apple.securityd_service.plist
com.apple.sessionlogoutd.plist
com.apple.smb.preferences.plist
com.apple.smbd.plist
com.apple.softwareupdate_download_service.plist
com.apple.softwareupdate_firstrun_tasks.plist
com.apple.softwareupdated.plist
com.apple.speech.speechsynthesisd.plist
com.apple.spindump.plist
com.apple.startupdiskhelper.plist
com.apple.statd.notify.plist
com.apple.storagekitd.plist
com.apple.storeaccountd.daemon.plist
com.apple.storeagent.daemon.plist
com.apple.storeassetd.daemon.plist
com.apple.storedownloadd.daemon.plist
com.apple.storereceiptinstaller.plist
com.apple.suhelperd.plist
com.apple.symptomsd.plist
com.apple.sysdiagnose.plist
com.apple.syslogd.plist
com.apple.sysmond.plist
com.apple.system_installd.plist
com.apple.systemkeychain.plist
com.apple.systempreferences.installer.plist
com.apple.systemstats.analysis.plist
com.apple.systemstats.daily.plist
com.apple.systemstatsd.plist
com.apple.taskgated-helper.plist
com.apple.taskgated.plist
com.apple.tccd.system.plist
com.apple.thermald.plist
com.apple.trustd.plist
com.apple.ucupdate.plist
com.apple.uninstalld.plist
com.apple.unmountassistant.sysagent.plist
com.apple.updateEFIDesktopPicture.plist
com.apple.usbd.plist
com.apple.usbmuxd.plist
com.apple.uucp.plist
com.apple.var-db-dslocal-backup.plist
com.apple.vsdbutil.plist
com.apple.warmd.plist
com.apple.watchdogd.plist
com.apple.wdhelper.plist
com.apple.wifid.plist
com.apple.wirelessproxd.plist
com.apple.wwand.plist
com.apple.xpc.smd.plist
com.apple.xpc.uscwoap.plist
com.apple.xsan.plist
com.apple.xsandaily.plist
com.apple.xscertadmin.plist
com.apple.xscertd-helper.plist
com.apple.xscertd.plist
com.vix.cron.plist
exec.plist
finger.plist
ftp.plist
login.plist
ntalk.plist
org.apache.httpd.plist
org.cups.cups-lpd.plist
org.cups.cupsd.plist
org.net-snmp.snmpd.plist
org.ntp.ntpd.plist
org.openldap.slapd.plist
org.postfix.master.plist
org.postfix.newaliases.plist
shell.plist
ssh.plist
telnet.plist
tftp.plist
```

"First" Process:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/CSIOS/FirstProcessOSX.png">

Network Settings:

<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/CSIOS/NextworkSettingsOSX.png">

#### Windows OS:

Pre-OS:
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/3/bios-1.jpg">
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/3/bios-2.jpg">

Kernel:
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/3/Kernel.PNG">

First Process:
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/3/FirstProcess.PNG">

StartUp Programs: <br>
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/3/StartupProgs.PNG">

Network Settings:
<img src="https://github.com/trixr4kdz/cmsi387/blob/master/images/3/NetSettings.PNG">





