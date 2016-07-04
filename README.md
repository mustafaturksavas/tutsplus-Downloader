tutsplus-Downloader
===================

This is an Automator workflow to download the videos of tutsplus courses for members who already has access for downloading. This workflow just enables you to sit back and relax while Safari downloads the courses for you.

## How Does it Work?
Script downloads the course videos, course files and put them inside a course folder. It runs as long as there are open Safari tabs, since it closes after downloading the course. And it stops when there are no tabs open. So, it's best to only open the courses you need downloading on Safari.

*Process*:

- Script downloads the first file of the tutorial and waits as long as the *delay_time* which is set for 2 minutes by default.

- When all videos are started downloading, it waits as long as the *delay_time* for one last time and it checks if there are course files to be downloaded.

- Script waits as long as the *extra_delay* which is set for 2 minutes by default.

- It creates a folder with a name of the course and moves the videos inside that folder.

- It checks if there are any Github links and creates a hyperlink and puts it inside the course folder.

- Script closes the courses tab and repeats the process until there are no tabs left.

## But Why?
If you want a course to be ready while you are doing something else, this might be what you need. Because sometimes you need another course ready while watching one or you want a couple courses downloaded while you are asleep.
