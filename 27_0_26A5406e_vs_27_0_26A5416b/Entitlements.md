## 🔑 Entitlements

### filesystem

### Journal

> `/System/Applications/Journal.app/Contents/MacOS/Journal`

```diff

 		<string>com.apple.stickers.recency</string>
 		<string>com.apple.cdp.daemon</string>
 		<string>com.apple.feedbackd.centralized-feedback</string>
+		<string>com.apple.generativeexperiences.availabilityService</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-only</key>
 	<array>

 		<string>com.apple.CloudSubscriptionFeatures.datadetectors</string>
 		<string>com.apple.GenerativeFunctions.GenerativeFunctionsInstrumentation</string>
 		<string>com.apple.generativeexperiences.availabilityService</string>
+		<string>com.apple.gms.availability</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-write</key>
 	<array>

```
### ControlStrip

> `/System/Library/CoreServices/ControlStrip.app/Contents/MacOS/ControlStrip`

```diff

 	<true/>
 	<key>com.apple.private.screencapture.allow</key>
 	<true/>
+	<key>com.apple.private.system-banner-client</key>
+	<true/>
 	<key>com.apple.private.touchbar.user-device</key>
 	<true/>
 </dict>

```
### ScreenTimeWidgetExtension

> `/System/Library/CoreServices/Screen Time.app/Contents/PlugIns/ScreenTimeWidgetExtension.appex/Contents/MacOS/ScreenTimeWidgetExtension`

```diff

 	<true/>
 	<key>com.apple.private.screen-time</key>
 	<true/>
+	<key>com.apple.private.screen-time-settings</key>
+	<true/>
 	<key>com.apple.private.screen-time.persistence</key>
 	<true/>
 	<key>com.apple.private.screentime-communication</key>

 	<array>
 		<string>com.apple.ak.anisette.xpc</string>
 		<string>com.apple.ScreenTimeAgent.persistence</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
 		<string>com.apple.UsageTrackingAgent.private</string>
 		<string>com.apple.familycircle.agent</string>
 		<string>com.apple.accountsd.accountmanager</string>

 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.ScreenTimeAgent.settings</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
+		<string>com.apple.accountsd.accountmanager</string>
 		<string>com.apple.biome.access.system</string>
 		<string>com.apple.biome.access.user</string>
+		<string>com.apple.familycircle.agent</string>
 		<string>com.apple.ManagedSettingsAgent</string>
 	</array>
 	<key>fairplay-client</key>

```
### ScreenTimeWidgetIntentsExtension

> `/System/Library/CoreServices/Screen Time.app/Contents/PlugIns/ScreenTimeWidgetIntentsExtension.appex/Contents/MacOS/ScreenTimeWidgetIntentsExtension`

```diff

 	<true/>
 	<key>com.apple.private.coreservices.canmaplsdatabase</key>
 	<true/>
+	<key>com.apple.private.familycircle</key>
+	<true/>
 	<key>com.apple.private.screen-time</key>
 	<true/>
+	<key>com.apple.private.screen-time-settings</key>
+	<true/>
 	<key>com.apple.private.screen-time.persistence</key>
 	<true/>
 	<key>com.apple.private.screentime-communication</key>

 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.ScreenTimeAgent.settings</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
+		<string>com.apple.familycircle.agent</string>
+		<string>com.apple.accountsd.accountmanager</string>
 	</array>
 </dict>
 </plist>

```
### Appearance

> `/System/Library/ExtensionKit/Extensions/Appearance.appex/Contents/MacOS/Appearance`

```diff

 <dict>
 	<key>com.apple.PerfPowerServices.data-donation</key>
 	<true/>
+	<key>com.apple.authkit.client.internal</key>
+	<true/>
 	<key>com.apple.private.SkyLight.screencapturedirect</key>
 	<true/>
 	<key>com.apple.private.launchservices.changedefaulthandlers</key>

 	<array>
 		<string>com.apple.powerlog.plxpclogger.xpc</string>
 		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>
+		<string>com.apple.ak.auth.xpc</string>
 	</array>
 </dict>
 </plist>

```
### accountsd

> `/System/Library/Frameworks/Accounts.framework/Versions/A/Support/accountsd`

```diff

 	<true/>
 	<key>com.apple.private.ind.client</key>
 	<true/>
+	<key>com.apple.private.intelligenceplatform.client-identifier</key>
+	<string>com.apple.accountsd</string>
 	<key>com.apple.private.keychain.allow-delete-internal-on-sign-out</key>
 	<true/>
 	<key>com.apple.private.ndoagent</key>

```
### ScreenTimeFollowUpExtension

> `/System/Library/PrivateFrameworks/ScreenTimeUI.framework/PlugIns/ScreenTimeFollowUpExtension.appex/Contents/MacOS/ScreenTimeFollowUpExtension`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>
+	<key>com.apple.accounts.appleidauthentication.defaultaccess</key>
+	<true/>
+	<key>com.apple.accounts.idms.fullaccess</key>
+	<true/>
+	<key>com.apple.itunesstored.private</key>
+	<true/>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>
+	<key>com.apple.private.applemediaservices</key>
+	<true/>
+	<key>com.apple.private.coreservices.canmaplsdatabase</key>
+	<true/>
+	<key>com.apple.private.familycircle</key>
+	<true/>
 	<key>com.apple.private.followup</key>
 	<true/>
+	<key>com.apple.private.managed-settings.effective-read</key>
+	<true/>
+	<key>com.apple.private.screen-time</key>
+	<true/>
+	<key>com.apple.private.screen-time-settings</key>
+	<true/>
+	<key>com.apple.private.screen-time.persistence</key>
+	<true/>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.DeviceActivity</string>
+	</array>
+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>
+	<key>com.apple.private.usage-tracking</key>
+	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
 	<key>com.apple.security.application-groups</key>
 	<array>
 		<string>group.com.apple.ScreenTime</string>
 	</array>
+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.DeviceActivity</string>
+	</array>
+	<key>com.apple.security.network.client</key>
+	<true/>
+	<key>com.apple.security.system-groups</key>
+	<array>
+		<string>systemgroup.com.apple.DeviceActivity</string>
+	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.accountsd.accountmanager</string>
 		<string>com.apple.corefollowup.agent</string>
+		<string>com.apple.familycircle.agent</string>
+		<string>com.apple.ManagedSettingsAgent</string>
+		<string>com.apple.ScreenTimeAgent.private</string>
+		<string>com.apple.ScreenTimeAgent.settings</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
+		<string>com.apple.UsageTrackingAgent.private</string>
 	</array>
 </dict>
 </plist>

```


### SystemOS

### com.apple.WebKit.Networking

> `/System/Library/Frameworks/WebKit.framework/Versions/A/XPCServices/com.apple.WebKit.Networking.xpc/Contents/MacOS/com.apple.WebKit.Networking`

```diff

 	<true/>
 	<key>com.apple.private.security.enable-state-flags</key>
 	<array>
+		<string>BlockNetworkAccess</string>
 		<string>BlockEnhancedSecurityLinks</string>
 	</array>
 	<key>com.apple.private.security.message-filter</key>
 	<true/>
 	<key>com.apple.private.security.mutable-state-flags</key>
 	<array>
+		<string>BlockNetworkAccess</string>
 		<string>BlockEnhancedSecurityLinks</string>
 	</array>
 	<key>com.apple.private.tcc.manager.check-by-audit-token</key>

```
### com.apple.WebKit.Networking

> `/System/Library/Frameworks/WebKit.framework/Versions/Current/XPCServices/com.apple.WebKit.Networking.xpc/Contents/MacOS/com.apple.WebKit.Networking`

```diff

 	<true/>
 	<key>com.apple.private.security.enable-state-flags</key>
 	<array>
+		<string>BlockNetworkAccess</string>
 		<string>BlockEnhancedSecurityLinks</string>
 	</array>
 	<key>com.apple.private.security.message-filter</key>
 	<true/>
 	<key>com.apple.private.security.mutable-state-flags</key>
 	<array>
+		<string>BlockNetworkAccess</string>
 		<string>BlockEnhancedSecurityLinks</string>
 	</array>
 	<key>com.apple.private.tcc.manager.check-by-audit-token</key>

```


### AppOS

### AuthenticationServicesAgent

> `/usr/libexec/AuthenticationServicesAgent`

```diff

 	<true/>
 	<key>com.apple.private.keychain.kcsharing.client</key>
 	<true/>
+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>
 	<key>com.apple.private.octagon</key>
 	<true/>
 	<key>com.apple.private.security.storage.Safari</key>

```


