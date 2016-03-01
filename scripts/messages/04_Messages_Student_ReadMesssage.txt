openURL|$url
verifyText|$gatewayText
click|ctoolsLogin

verifyText|$kerberosLoginPageText
enterText|login|$studUser
enterText|password|$studPass

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

comment|Open the folder that should have a message from the instructor
click|Received
verifyText|Instructor Test Message
verifyText|$instUser
verifyValue|View|All Messages

click|Instructor Test Message
verifyText|High
verifyText|A hearty hello to you.
verifyText|Instructor Test Message

click|TestAttachment.doc
verifyFile|TestAttachment.doc

click|Logout
verifyText|You are about to log out

click|Log Out
verifyText|$logoutText
