# Binging with Babish Youtube Dataset

## Overview
Video views and details collected from the Binging with Babish Youtube channel collected using [yt-datasets](https://github.com/wangw05/yt-datasets). The dataset was collected on Aug. 25th, 2020.

## Usage
Download csv to conduct further analysis.

## Data Collected from Youtube
| Column Name   | Definition                                                   |
|---------------|--------------------------------------------------------------|
| etag       | [HTTP ETag](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/ETag), an unique identifier for a resource.                    |
| videoid       | id of video uploaded, unique to each video                   |
| channelid     | id of channel uploader, unique to each channel               |
| publishedtime | publish time of video, in the format of YYYY-MM-DDThh:mm:ssZ |
| title         | title of the video                                           |
| desc          | description of the video                                     |
| live          | whether the video is an upcoming livestream, ongoing livestream, or neither                           |
| viewcount     | viewcount of the video at time of request                    |
| likecount     | likecount of the video at time of request, -1 indicates no data found                    |
| dislikecount  | dislikecount of the video at time of request, -1 indicates no data found                 |
| comments      | list of all main-level comments on video, saved in utf8      |
| commentcount  | count of all main-level comments                             |
| tags          | list of tags added by video uploader for video                       |

## Special Considerations
The first entry of the dataset, titled "[Binging with Babish: Meat Tornado from Parks & Rec](https://www.youtube.com/watch?v=LsNg-KrFxCA)", was uploaded on the same day as the data collection date. Metrics from this video may be an outlier to the data.

Two videos ([One Pot Pastas | Basics with Babish](https://www.youtube.com/watch?v=cs8OYby6RrA) and [Binging with Babish Live: Q&A and Behind-the-Scenes](https://www.youtube.com/watch?v=J_8vByvEQJM)) did not have any tags listed.

One video ([Water-Proof Trailer](https://www.youtube.com/watch?v=RwGfqexvlts)) did not have any public like/dislike information listed.
