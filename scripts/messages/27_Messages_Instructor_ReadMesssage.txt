openURL|$url
verifyText|$gatewayText
click|ctoolsLogin

verifyText|$kerberosLoginPageText
enterText|login|$instUser
enterText|password|$instPass

click|doLogin
verifyText|Assignments & Events
verifyText|Recent Activity

click|$site
verifyText|Site Information Display
verifyText|viewing announcements from the last 10 days

click|Messages
verifyText|Received
verifyText|Sent
verifyText|Deleted
verifyText|1 message - 1 unread
verifyText|Messages

comment|Open the folder that should have a message from the student
click|Received
verifyText|Student Test Message
verifyText|$studUser
verifyValue|View|All Messages

click|Student Test Message
verifyText|A hearty hello to you.
verifyText|Student Test Message

click|TestAttachment.doc
verifyFile|TestAttachment.doc

click|Logout
verifyText|You are about to log out

click|Log Out
verifyText|$logoutText
