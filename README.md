# Musical Ties
It can be difficult to find the perfect playlist for a given mood or occasion. Existing visualizations of music do not organize information in a way that allows the user to easily navigate the data and create their own playlists. Musical Ties is a platform that provides visualizations for musical playlists and songs. It guides the user through the process of exploring new music and understanding metrics that make up different playlists. With this platform, they are able to curate a new playlist that fits their desires.

Visualization:  https://6859-sp21.github.io/final-project-musical-ties/  
Paper: [](/final/musical_ties.pdf)
Video: https://www.youtube.com/watch?v=JnEeRpoNXQI&feature=youtu.be  

By Violetta Jusiega and Shariqah Hossain  

![Musical Ties](/images/home.png)

The [Spotify API](https://developer.spotify.com/) was used to get top Spotify playlists and metrics about the songs within the playlists. 

## Development Process 
We met frequently to discuss the plan and design for the project. We started with rough sketches, but eventually transitioned to Figma. These tools were very useful when iterating on our design.

One of the hardest things about this project was creating our custom visualizations. Although many components started as references from existing D3 examples, they required a lot of modification to reach the level of cohesive design and interactivity that we were aimining for. We also wanted to create visualizations that were able to portray many data points in a small amount of space. This as well as the record-inspired theme of the website led us to spend extra time ensuring that the user was able to parse through the data easily and navigate the website with minimal friction.

We originally thought that our project would fit on a single page view, but decided to go toward multi-page view so that we can fit more information without things being cramped. Another challenge was ensuring that the different pages were still cohesive and communicated with each other effectively. We also iterated on the types of sorting and filtering functionality that would be available to the user and what would make the most sense for them to use. 

### Shared Work 
Together, Shariqah and Violetta spent a lot of time working on their design on Figma so that they could have a strong plan of what they wanted to implement. This helped them create a color scheme as well as to think through some of the more abstract parts of their design. 

In the next two sections we list components of the project we worked on, with each person. 

### Shariqah's Work 
* Playlist Exploration Page 
  * radial slider for filtering
  * filtering implementation
* Playlist View / Comparison Page
  * radial slider for filtering
  * filtering implementation
  * song list
  * remove song from your playlist
  * publish your playlist
  * rename your playlist
  * select song
   * song player in selected song in list
   * scroll to song in list
   * bar graph
   * add song to your playlist
* Page layout and communicating data between pages
 
### Violetta's Work 
* Data gathering from Spotify API
* Help / Information section 
* Playlist Exploration Page 
  * radial playlist visualization 
  * tooltips
  * functionality for visually moving playlists and hiding playlists 
  * playlist sort functionality + visualization
* Playlist View / Comparison Page
  * stacked radial bar chart representation 
  * sort playlist functionality + visualization 
  * select focus feature functionality + visualization 


