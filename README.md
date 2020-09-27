# Google-IT-Support-Specialist-Ultimate-notes

This repository contains the transcripts and the screenshots of the Coursera course https://www.coursera.org/professional-certificates/google-it-support.

Feel free to star the repo and contribute by editing the Word version of the documents.

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
                   
