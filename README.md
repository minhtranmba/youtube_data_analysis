<i>This is Part II</i>.<br>
To understand what people watch the most on Youtube in the US, I gathered video's data through [Youtube API v3](https://developers.google.com/youtube/v3/docs). The results returned by Search query via Youtube API contain approximately 200 records for each year from 2018 to 2022. Records are ordered by the number of views in descending order, telling us the most watched videos on Youtube. The dataset includes information below:
<ul>
    <li>Video Title</li>
    <li>Video ID</li>
    <li>Publish Date</li>
    <li>Channel Title</li>
    <li>Channel ID</li>
    <li>Video Category</li>
    <li>Video Duration</li>
    <li>Number of Views</li>
    <li>Number of Likes</li>
    <li>Number of Comments</li>
</ul>
Through this dataset, I will perform analyses to get a deeper understanding of:
<ol>
    <li>What are the most popular video categories?</li>
    <li>Does the viewer's preference change before and during Covid (considering we are still in Covid time)?</li>
    <li>What is viewer's preference for video's length?</li>
    <li>What are the best days in month to publish a video?</li>
    <li>Is there a linear relationship between number of views and likes/comments?</li>
</ol>
