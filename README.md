# Google-IT-Support-Specialist-Ultimate-notes

This repository contains the transcripts and the screenshots of the Coursera course https://www.coursera.org/professional-certificates/google-it-support.

Feel free to star the repo and contribute by editing the Word version of the documents (located in the `word/` subfolder of each course).

## 📚 Course structure

### 01 - Technical Support Fundamentals

- [01 Introduction to IT](01-technical-support-fundamentals/01%20Introduction%20to%20IT.md)
- [02 Hardware](01-technical-support-fundamentals/02%20Hardware.md)
- [03 Operating systems](01-technical-support-fundamentals/03%20Operating%20systems.md)
- [04 Networking](01-technical-support-fundamentals/04%20Networking.md)
- [05 Software](01-technical-support-fundamentals/05%20Software.md)

### 02 - Computer Networking

- [01 Introduction to networking](02-computer-networking/01%20Introduction%20to%20networking.md)
- [02 The network layer](02-computer-networking/02%20The%20network%20layer.md)
- [03 The transport and application layers](02-computer-networking/03%20The%20transport%20and%20application%20layers.md)
- [03.5 Homework - All layers working in unison](02-computer-networking/03.5%20Homework%20-%20All%20layers%20working%20in%20unison.md)
- [04 Networking services](02-computer-networking/04%20Networking%20services.md)
- [05 Connecting to the internet](02-computer-networking/05%20Connecting%20to%20the%20internet.md)
- [06 Troubleshooting and the future of networking](02-computer-networking/06%20Troubleshooting%20and%20the%20future%20of%20networking.md)

### 03 - Operating Systems and You: Becoming a Power User

- [01 Navigating the system](03-os-power-user/01%20Navigating%20the%20system.md)
- [02 Users and permissions](03-os-power-user/02%20Users%20and%20permissions.md)
- [03 Package and software management](03-os-power-user/03%20Package%20and%20software%20management.md)
- [04 File systems](03-os-power-user/04%20File%20systems.md)
- [05 Process management](03-os-power-user/05%20Process%20management.md)
- [06 Operating systems in practice](03-os-power-user/06%20Operating%20systems%20in%20practice.md)

### 04 - System Administration and IT Infrastructure Services

- [01 What is system administration](04-system-administration-it-infrastructure-services/01%20What%20is%20system%20administration.md)
- [02 Network and infrastructure services](04-system-administration-it-infrastructure-services/02%20Network%20and%20infrastructure%20services.md)
- [03 Software and platform services](04-system-administration-it-infrastructure-services/03%20Software%20and%20platform%20services.md)
- [04 Directory services](04-system-administration-it-infrastructure-services/04%20Directory%20services.md)
- [05 Data recovery backups](04-system-administration-it-infrastructure-services/05%20Data%20recovery%20backups.md)
- [06 Final project](04-system-administration-it-infrastructure-services/06%20Final%20project.md)

### 05 - IT Security: Defense against the Digital Dark Arts

- [01 Understanding security threats](05-it-security/01%20Understanding%20security%20threats.md)
- [02 Pelcgbybtl cryptology](05-it-security/02%20pelcgbybtl%20cryptology.md)
- [03 AAA security not roadside assistance](05-it-security/03%20aaa%20security%20not%20roadside%20assistance.md)
- [04 Securing your network](05-it-security/04%20Securing%20your%20network.md)
- [05 Defense in depth](05-it-security/05%20Defense%20in%20depth.md)
- [06 Creating a company culture for security](05-it-security/06%20Creating%20a%20company%20cultre%20for%20security.md)

## 📁 Repository layout

```
├── 01-technical-support-fundamentals/
│   ├── *.md          ← Course notes (Markdown)
│   ├── media/        ← Screenshots and images
│   ├── word/         ← Original Word documents
│   └── pdf/          ← PDF exports
├── 02-computer-networking/
│   ├── *.md
│   ├── media/
│   ├── word/
│   └── pdf/
├── 03-os-power-user/
│   ├── *.md
│   ├── media/
│   ├── word/
│   └── pdf/
├── 04-system-administration-it-infrastructure-services/
│   ├── *.md
│   ├── media/
│   ├── word/
│   └── pdf/
└── 05-it-security/
    ├── *.md
    ├── media/
    ├── word/
    └── pdf/
```

## Download Coursera courses

This is a quick user guide to download a Coursera course. Source from `coursera-dl` https://github.com/coursera-dl/coursera-dl

0) Install Anaconda and python. Use the Anaconda prompt to run the commands below. Install with 
`pip install coursera-dl`

1) Download/clone repository https://github.com/coursera-dl/coursera-dl
2) Login to https://www.coursera.org/
3) Go to the welcome page of the course you want to download. Subscribe to the course and copy the name of the course in the URL
For example:  https://www.coursera.org/learn/technical-support-fundamentals/home/welcome 
gives > technical-support-fundamentals, 
https://www.coursera.org/learn/it-security/home/welcome gives > it-security

3) Just Login to https://learner.coursera.help/hc/en-us

4) Close all windows in the browser related to Coursera, including the one in the previous step

5) In the terminal, go in the same folder as coursera-dl-master that contains the script (be aware of the clone repo due to the unzip)
Path of the readme of the repo: `path\Downloads\coursera-dl-master\coursera-dl-master\README.md`
Where to go in the terminal: `path\Downloads\coursera-dl-master`

6) Type at the end of the following command the name of the course you want to download, from the URL.

Warning: you may run this command 10 times until it works. If it fails, wait 5-10 minutes and try again.


For example:
- coursera-dl -u youremail -p yourpassword --subtitle-language en --download-quizzes --download-notebooks --video-resolution 720p technical-support-fundamentals
- coursera-dl -u youremail -p yourpassword --subtitle-language en --download-quizzes --download-notebooks --video-resolution 720p it-security
- coursera-dl -u youremail -p yourpassword --subtitle-language en --download-quizzes --download-notebooks --video-resolution 720p technical-support-fundamentals
- coursera-dl -u youremail -p yourpassword --subtitle-language en --download-quizzes --download-notebooks --video-resolution 720p computer-networking
- coursera-dl -u youremail -p yourpassword --subtitle-language en --download-quizzes --download-notebooks --video-resolution 720p os-power-user
- coursera-dl -u youremail -p yourpassword --subtitle-language en --download-quizzes --download-notebooks --video-resolution 720p system-administration-it-infrastructure-services
- coursera-dl -u youremail -p yourpassword --subtitle-language en --download-quizzes --download-notebooks --video-resolution 720p it-security


Now the course is downloaded in local. 
You can do it even during the trial period ;)
Here are all the options of the command:

`coursera-dl [-h] [-u USERNAME] [-p PASSWORD] [--jobs JOBS]
                   [--download-delay DOWNLOAD_DELAY] [-b] [--path PATH]
                   [-sl SUBTITLE_LANGUAGE] [--specialization]
                   [--only-syllabus] [--download-quizzes]
                   [--download-notebooks] [--about] [-f FILE_FORMATS]
                   [--ignore-formats IGNORE_FORMATS] [-sf SECTION_FILTER]
                   [-lf LECTURE_FILTER] [-rf RESOURCE_FILTER]
                   [--video-resolution VIDEO_RESOLUTION]
                   [--disable-url-skipping] [--wget [WGET]] [--curl [CURL]]
                   [--aria2 [ARIA2]] [--axel [AXEL]]
                   [--downloader-arguments DOWNLOADER_ARGUMENTS]
                   [--list-courses] [--resume] [-o] [--verbose-dirs] [--quiet]
                   [-r] [--combined-section-lectures-nums]
                   [--unrestricted-filenames] [-c COOKIES_FILE] [-n [NETRC]]
                   [-k] [--clear-cache] [--hook HOOKS] [-pl]
                   [--mathjax-cdn MATHJAX_CDN_URL] [--skip-download] [--debug]
                   [--cache-syllabus] [--version] [-l LOCAL_PAGE]
                   [class_names [class_names ...]]`
                   
