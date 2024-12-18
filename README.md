# **YouTube Channel Analysis: My Most Watched Channels** 📺📊  

## **Overview** ✍️  
This project analyzes my YouTube viewing habits by examining data from my most-watched channels. The analysis involves cleaning and processing YouTube data, exploring trends in engagement, content preferences, and validating common myths about successful videos. The goal is to extract meaningful insights into my personal preferences and broader patterns across the YouTube platform.  

---  

![YouTube Data](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/YT.jpeg)

---  

## **Skills Demonstrated** 💡  
- **YouTube API**: Fetching video metadata such as views, likes, comments, tags, and upload dates.  
- **Data Cleaning and Transformation**: Standardizing inconsistent fields like video titles, durations, and tags.  
- **Text Analysis**: Extracting trending topics from video titles using Natural Language Processing (NLP).  
- **Visualization**: Creating insights through interactive and static visualizations.  

---  

## **Aims and Objectives** 🎯  

Within this project, I would like to explore the following:

- Getting to know YouTube API and how to obtain video data.
- Analyzing video data and verify different common "myths" about what makes a video do well on YouTube, for example:
    - Does the number of likes and comments matter for a video to get more views?
    - Does the video duration matter for views and interaction (likes/comments)?
    - Does title length matter for views?
    - How many tags do good performing videos have? What are the common tags among these videos?
    - Across all the creators I take into consideration, how often do they upload new videos? On which days in the week?
- Explore the trending topics using NLP techniques
    - Which popular topics are being covered in the videos (e.g. using wordcloud for video titles)?

---

## **Charts and Visualizations** 📈  

### **1. Subscribers per Channel** 👥  
This bar chart visualizes the number of subscribers across different YouTube channels.  

![Subscribers per Channel](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/SPC.png)

---

### **2. Views per Channel** 👁️  
This bar chart shows the total number of views per channel.  

![Views per Channel](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/VPC.png)

### **3. Views per Channel using Violin** 🎻  
This violin plot shows the distribution of views across different YouTube channels. It helps to visualize how views are spread across the channels in your dataset.

![Views per Channel](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/VVPC.png)

### **4. Distribution of Video Durations** ⏱️  
This histogram shows the distribution of video durations (in hours) for videos with a duration of less than 10,000 seconds. It gives an insight into how long most of the videos are in the dataset.

![Distribution of Video Durations](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/DISTOFVDHR.png)

### **5. Title Length vs View Count** 📝  
This scatter plot shows the relationship between the length of video titles (in characters) and their corresponding view counts. The visualization provides insights into whether the title length impacts video performance.  

![Title Length vs View Count](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/TL.png)

### **6. Duration vs Comments & Likes** 📊  
These scatter plots compare the relationship between video duration and the number of comments/likes for the videos in the dataset.

![Duration vs Comments & Likes](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/DSS.png)

### **7. Word Cloud of Video Titles** 💬  
This word cloud represents the most frequently used words in video titles across the dataset. The larger the word, the more frequently it appears.

![Word Cloud](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/WC.png)

### **8. View Count vs Comment and Like Count** 📊  
This scatter plot visualizes the relationship between video view counts and the corresponding comment and like counts. It highlights how engagement metrics, such as comments and likes, correlate with viewership.  

![View Count vs Comment and Like Count](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/CCLC.png)

### **9. View Count and Like Count vs Comment Ratio** 📊  
This scatter plot illustrates the relationship between view counts, like counts, and the comment-to-view ratio for videos. It provides insights into how engagement through likes and comments correlates with video viewership.  

![View Count and Like Count vs Comment Ratio](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/CRLR.png)

### **10. Tags Count vs Views** 📑  
This scatter plot shows how the number of tags associated with a video correlates with the number of views it receives.

![Tags Count vs Views](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/NTNV.png)

### **11. Videos Published by Day of the Week** 📅  
This bar plot shows the distribution of videos published across different days of the week. It helps visualize the most common days on which videos are uploaded.

![Videos Published by Day](https://github.com/Naveennnkumar-Bit/My-YouTube-Watch-Habits/blob/main/charts/DOW.png)

---

## **Tools Used** 🛠️  
- **Python**: For data processing and analysis.  
- **YouTube Data API**: To retrieve metadata for videos and channels.  
- **Libraries**: Pandas, Matplotlib, Seaborn, WordCloud, NLTK, Plotly.  

---  

## **Key Takeaways** 📌  
- A comprehensive understanding of my most-watched YouTube channels and viewing patterns.  
- Insights into factors contributing to video performance, such as likes, comments, duration, and tags.  
- Identification of trending topics and content preferences across channels.  

---  

## **Future Improvements** 🚀  
- Expand the analysis to include sentiment analysis on video comments.  
- Create predictive models to estimate view counts based on video metadata.  
- Develop interactive dashboards for real-time trend analysis and visualization.  

---  
