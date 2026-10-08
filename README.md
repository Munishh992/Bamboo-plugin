# Leapwork Integration
This is Leapwork plugin for Bamboo

# More Details
Leapwork is a mighty automation testing system and now it can be used for running [smoke, functional, acceptance] tests, generating reports and a lot more in Bamboo. You can easily configure integration directly in Bamboo enjoying UI friendly configuration page with easy connection and test suites selection.

# Features:
 - Setup and test Leapwork connection in few clicks
 - Run automated tests in your Bamboo build tasks
 - Automatically receive test results
 - Build status based tests results
 - Generate a xml report file in JUnit format
 - Write tests trace to build output log
 - Smart UI
 
# Installing
- Use atlassian-sdk maven 8.0.7
- Command: atlas-package 
- Or download jar file of OBR file from Releases section.

# Instruction
1. Add Build "Leapwork Integration" to your job.
2. Enter your Leapwork controller hostname or IP-address something like "win10-agent20" or "localhost".
3. Enter your Leapwork controller API port, by default it is 9001.
4. Enter JUnit report file name. This file will be created at your job's working directory. If there is an xml file with the same name, it will be overwritten. By default it is "report.xml".
5. Enter time delay in seconds. When schedule is run, plugin will wait this time before trying to get schedule state. If schedule is still running, plugin will wait this time again. By default this value is 5 seconds.
6. Select how plugin should set "Done" status value: to Success or Failed.
7. Press button "Select Schedules" to get a list of all available schedules. Select schedules you want to run.
8. Add Post-Build "Publish JUnit test result report" to your job. Enter JUnit report file name. It MUST be the same you've entered before!
9. Run your job and get results. Enjoy!

# Screenshots
![ScreenShot](https://github.com/leapwork/Bamboo-plugin/blob/master/src/main/resources/images/image1.png)
![ScreenShot](https://github.com/leapwork/Bamboo-plugin/blob/master/src/main/resources/images/image2.png)
![ScreenShot](https://github.com/leapwork/Bamboo-plugin/blob/master/src/main/resources/images/image3.png)

- Git versioning access validated by Leapwork at 2026-09-23 11:30:37 UTC.

- Git versioning access validated by Leapwork at 2026-09-23 12:02:14 UTC.

- Git versioning access validated by Leapwork at 2026-09-23 12:33:28 UTC.

- Git versioning access validated by Leapwork at 2026-09-23 13:19:05 UTC.

- Git versioning access validated by Leapwork at 2026-09-23 13:22:41 UTC.

- Git versioning access validated by Leapwork at 2026-09-24 07:18:58 UTC.

- Git versioning access validated by Leapwork at 2026-09-24 12:52:45 UTC.

- Git versioning access validated by Leapwork at 2026-09-24 13:07:13 UTC.

- Git versioning access validated by Leapwork at 2026-09-24 13:12:45 UTC.

- Git versioning access validated by Leapwork at 2026-09-24 13:14:35 UTC.

- Git versioning access validated by Leapwork at 2026-09-24 13:18:49 UTC.

- Git versioning access validated by Leapwork at 2026-09-24 13:25:59 UTC.

- Git versioning access validated by Leapwork at 2026-09-24 13:26:36 UTC.

- Git versioning access validated by Leapwork at 2026-09-28 08:27:13 UTC.

- Git versioning access validated by Leapwork at 2026-09-28 08:44:17 UTC.

- Git versioning access validated by Leapwork at 2026-09-28 14:06:06 UTC.

- Git versioning access validated by Leapwork at 2026-09-28 14:15:32 UTC.

- Git versioning access validated by Leapwork at 2026-09-28 15:17:55 UTC.

- Git versioning access validated by Leapwork at 2026-09-28 17:40:00 UTC.

- Git versioning access validated by Leapwork at 2026-09-28 17:44:50 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 06:47:41 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 06:52:29 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 06:53:29 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 07:00:59 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 07:02:17 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 07:07:41 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 07:08:18 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 07:14:18 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 07:22:46 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 07:23:27 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 07:43:48 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 07:50:12 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 07:54:44 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 08:00:07 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 08:05:41 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 08:07:35 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 08:52:11 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 09:00:51 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 10:24:31 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 10:29:35 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 10:44:35 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 10:48:54 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 11:41:08 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 11:56:51 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 12:02:35 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 12:03:40 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 12:13:56 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 12:43:31 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 12:49:34 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 12:54:59 UTC.

- Git versioning access validated by Leapwork at 2026-09-29 13:17:32 UTC.

- Git versioning access validated by Leapwork at 2026-09-30 12:10:05 UTC.

- Git versioning access validated by Leapwork at 2026-09-30 12:13:39 UTC.

- Git versioning access validated by Leapwork at 2026-09-30 12:30:55 UTC.

- Git versioning access validated by Leapwork at 2026-09-30 13:29:51 UTC.

- Git versioning access validated by Leapwork at 2026-09-30 14:19:28 UTC.

- Git versioning access validated by Leapwork at 2026-09-30 14:24:51 UTC.

- Git versioning access validated by Leapwork at 2026-09-30 14:29:52 UTC.

- Git versioning access validated by Leapwork at 2026-09-30 15:08:10 UTC.

- Git versioning access validated by Leapwork at 2026-09-30 15:15:42 UTC.

- Git versioning access validated by Leapwork at 2026-10-01 06:06:44 UTC.

- Git versioning access validated by Leapwork at 2026-10-01 12:45:14 UTC.

- Git versioning access validated by Leapwork at 2026-10-01 13:07:22 UTC.

- Git versioning access validated by Leapwork at 2026-10-01 17:03:32 UTC.

- Git versioning access validated by Leapwork at 2026-10-01 17:49:21 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 12:42:56 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 13:33:34 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 13:40:40 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 13:59:17 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 14:28:28 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 14:35:46 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 14:46:56 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 14:48:47 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 14:50:03 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 14:53:52 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 14:56:12 UTC.

- Git versioning access validated by Leapwork at 2026-10-08 17:20:33 UTC.
