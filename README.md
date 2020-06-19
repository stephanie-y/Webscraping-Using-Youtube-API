# Webscraping-Youtube-with-Python

Webscraping information on various channels using Google's Youtube API v3 and Python.

YouTube API makes webscraping very simple. The data collected can be extremely useful for analysis such as how video titles are related with number of views, most commonly used words in video titles, average playlist lengths and so on. 
I will be uploading various Python notebooks that show you how to gather data for your own projects!

**1) scraping-githubs-channel.ipynb:** This notebook shows you how to gather the title, description, and publish date of all videos of any YouTube channel. You can store this information into a csv, xlsx, or just keep it as a list of json data. The collected video ids can be used as a separate list to scrape the videos statistics of each video as well.

**2) get-video-info.ipynb:** This notebook shows you how to use the video id data gathered from the above notebook to grab YouTube statistics for each video id.

# Datasets: 

1. **github-videos.csv** contains: \
**Last Modified: June 19, 2020** 

| **Header**     | **Description** | **Data Type**     |
| :----:       |    :----   |         :----: |
| Video ID | The unique identifier for a YouTube video.| String |
| Date     | The publishing date of a video to a channel in **YYYY-MM-DD** format.   | String   |
| Channel ID  | The channel that uploaded the video.       | String      |
| Title   | The title of the video.        | String      |

2. **github-video-info.csv** contains: \ 
**Last Modified: June 19, 2020**

| **Header**     | **Description** | **Data Type**     |
| :----:       |    :----   |         :----: |
| Video_ID | The unique identifier for a YouTube video.| String |
| Title | The title of the video.        | String      |
| Channel | The channel name that uploaded the video. | String      |
| Publish_Date | The publishing date of a video to a channel in **YYYY-MM-DD** format.   | String   |
| Publish_Time | The time the video was published in UTC in **HH:MM:SS** format.    | String   |
| Views | The amount of views the video has received. | String   |
| Likes |The amount of 'likes' the video has received. | String   |
| Dislikes |The amount of 'dislikes' the video has received. | String   |
| Comment_Count |The amount of comments a video has received. | String   |
| Video_Tags | The tags created by the uploader associated with the video. | String   |
| Video_Description | The video description written by the uploader. | String   |
