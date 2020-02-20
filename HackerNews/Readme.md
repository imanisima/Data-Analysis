## Hacker News Posts

### Overview
---
[Hacker News](https://thehackernews.com) is similar to Reddit in that users submit posts that are voted and commented upon. This site is extremely important within the tech world, and helps users stay up to date on current events.

For the purposes of this project, the data has been significantly reduced from 300K rows to 20K by removing posts that have received no comments and then random sampling from the remaining pool.

### Column Descriptions
---
```id```: Unique identifier of a post.

```title```: Title of the post.

```url```: Post URL (if there is one).

```num_points```: The number of points the post acquired (total number of upvotes - the total number of downvotes).

```num_comments```: The number of comments that were made on the post.

```author```: The username of the person who submitted the post

```created_at```: The date and time at which the post was submitted

### Files
---
The csv file can be found [here](https://www.kaggle.com/hacker-news/hacker-news-posts). 
