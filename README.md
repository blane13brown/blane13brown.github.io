# Project 2: Personal Magic Mirror

## Requirements for a grade of C
  I designed my mirror using a column style grid to allow the design to be uniform and coherent. All controls line the sides of the mirror so that it can still 
be used as a simple mirror when the user stands in the middle. 
### Smart Mirror Sketch:

<p align="middle">
  <img src="https://user-images.githubusercontent.com/88754586/202023352-d6f97b3e-5d6c-4f5c-9bd1-50f74cc65875.png" width="90%">
</p>

### Design Choices
#### Clock
  The clock was designed to be simple and easy to read without any conscious effort from the user. It is positioned in the top left because that is where the users 
eyes are likely to look first since we read English left to right from top to bottom. It also includes the date and day to help transition into the next widget 
which is the personal calendar events. 

#### Calendar Events
  Calendar events are listed in the order in which they are scheduled and color coded to help users quickly see events that have already passed and those which are
still upcomming. These events are read in from the users reminder app on their phone where they can be altered and updated.

#### Weather
  The weather first lists your location along with the current temperature since this is the most important information that most users will want when viewing the
weather. It then lists the weather for the upcoming week using a weather API. Low temperatures are shown in a cold blue color while the main temperatures are
simply shown in black. Weather type is also described in simple terms instead of pictures to help avoid confusion from users.

#### News and Messages
  I decided to combine the personalized news feed, text messages and social media feeds all into one widget. All of these items are related and it made the most
sense to combine them so that the user interface is not too cluttered. Clicking the button with the icon of the app you want will switch the widgets view. As
you can see in the sketch the newspaper button is blue, meaning news is currently selected to display in the widget. 

#### Health Information

- Link to the GitHub repository: [p1.blane.brown](https://github.com/blane13brown/p1.blane.brown.git)

