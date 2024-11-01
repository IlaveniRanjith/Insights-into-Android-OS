# Prerequisites

<p>Before proceeding to download and compile the Android source code, make sure your system meets these requirements.</p>

## Hardware Requirements

Your development computer should have hardware that meets or surpasses these requirements:

* A 64-bit environment is required for Android 13.

* At least 250GB of free disk space to check out the code and an extra 150 GB to build it. If you conduct multiple builds, you need additional space.

* Google suggests having a minimum of 64 GB of RAM, and they do not perform testing with lower amounts. Having less RAM can result in builds being terminated due to out-of-memory (OOM) issues.

## Software Requirements

<p>The primary branch of AOSP is typically created and tested on Ubuntu Long Term Support (LTS) versions.</p>

**Operating system:**

* For developing the AOSP main branch, use Ubuntu 20.04 (LTS).

**JDK (Java development Kit):**

* The main branch of Android in AOSP comes with a prebuilt version of OpenJDK, so no additional installation is required.

**Key Packages:**

* Ensure that your system has Python 3 from python.org.
* The AOSP main branch comes with a prebuilt version of Make, so no additional installation is required.
* Make version - GNU Make 4.2.1 or Newer from gnu.org.
* Git version 2.25.1 or newer from git-scm.com.

{!docs/assets/abbreviations.txt!}
