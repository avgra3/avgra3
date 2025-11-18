# Antony G.

I am a naturally currious person who enjoys working with data and making useful tools. Throughout my career working with data, I have made multiple tools for myself and team to drive productivity and ease friction when working.

My Github is a short list of things I have created for myself and for work.

## Project Highlights

### Audio Converter

Since early 2024 I have gotten into listening to audiobooks. However, when using purchased audiobooks from Audible, I ran into issues with their proprietary file format on my laptop. To get around this, I looked for tools to help me convert my files to an easier to play format like mp4. I however, was curious of how to do this myself. This led me using FFMPEG to convert my files. FFMPEG is great but using the cli is a bit confusing and I was going to do the samme thing for multiple files. Thus [AudioConverter](https://github.com/avgra3/AudioConverter) was born.

This project is still in development but is functional as I am personally using it and making tweaks. This taught me how to use the file explorer to grab the path of a file and making a nice TUI. This project also usese C# for all logic.

### Database Changes

I have made a tool that allows for efficiently changing a databases parameters. It has been modified for different uses cases that include:

- Convert a database's engine to MyIsam from Aria
- Convert a database's collation from latin1 to utf8mb4
- Convert all char fields to varchar

This tool uses Python multiprocessing to automate getting a list of tables that need to be changed and then breaking that list into roughly equal sublists. The number of lists depends on the number of CPU cores available to the machine. It then generates the SQL required to make the changes to the tables and executes those SQL scripts in parallel. This tool has made making database wide changes easier for both myself and my collegues. Check it out the open version [here](https://github.com/avgra3/convert-database).

### Automation of ETL

Using Python to automate the ETL processing of new data. This project focused on automating the transformation of the data to be ready to send to our production databases. This essentially automates the processes that would normally need to be executed manually.

This was originally a process that was done using Alteryx but I moved it to use Python and SQL templating. This made it more modular and easier to use. I also added a configuration TOML file that is the only item that would need to be updated if database parameters change (username, password, hostname, etc.).

As a final update to the project, I made sure to use the Python multiprocessing module to run the 3 different portions run on the database. Greatly reducing the time it previously took to processes this dataset. In order to make it easier for anyone who uses this tool, I added logging and a simple CLI with a help command.


<!-- **`Data Analyst & Homelaber`** -->

<!--    <p align="left">
      <a href="https://github.com/avgra3?tab=followers">
         <img alt="followers" title="Follow me on Github" src="https://custom-icon-badges.demolab.com/github/followers/avgra3?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/></a>
      <a href="https://github.com/avgra3?tab=repositories&sort=stargazers">
         <img alt="total stars" title="Total stars on GitHub" src="https://custom-icon-badges.demolab.com/github/stars/avgra3?color=55960c&style=for-the-badge&labelColor=488207&logo=star"/></a>
   </p> -->

<!-- --- -->

<!-- ### 🧰 Languages and Tools
<img align="left" alt="MariaDB" width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mariadb/mariadb-original-wordmark.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" alt="Linux" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
<img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
<img align="left" alt="MySQL" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" />
<img align="left" alt="Bash" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />
<img align="left" alt="C#" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" />
<img align="left" alt="Docker" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain.svg" />
<img align="left" alt="Anaconda" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/anaconda/anaconda-original.svg" />
<img align="left" alt="Github" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original-wordmark.svg" />
<img align="left" alt="Django" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" />
<br /> -->

<!-- # -->

<!-- ### 📊 Stats
[![Antony's GitHub stats](https://github-readme-stats.vercel.app/api?username=avgra3&count_private=true&show_icons=true&theme=dracula)](https://github-readme-stats.vercel.app/api?username=avgra3)
 -->
<!-- # -->

<!-- <details>
 <summary><h3>👨‍💻 Antony's Coding Journey</h3></summary>
  I was first introduced to coding in college, where we used mathematical modeling to make predictions and simulate events. This was a difficult class as we only used the Python modules Numpy and Matplotlib. However, I got a taste for programming and began using it to make simple apps to help me with my college studies (mainly calculations and to verify hand calculated results). Once graduating I began working as a Data Analyst were I have mainly used coding to clean data and to make statistical observations. My personal projects on the other hand are used to solve problems or questions I may have. Currently, I am working on getting more into data science and machine learning to progress my career. As such, I expect to eventually create repositories of some of the material I have been working on. -->

<!-- raw links here -->
[MariaDB]: https://mariadb.com/about-us/
