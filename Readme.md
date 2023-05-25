# Dorf-Kalender with ICS-Download

### History
Every year we get a handout with the upcoming events. So I had the idea to provide the events as an ics-file for persons who want to include them in their smartphone calendar.  
Our village has a very simple homepage maintained by an aged volunteer, which means it have to be as simple as possible - one file pushed to the server and it works.  

### Description
Simple and minimalistic calendar list in a single file, for easy including in given HTML-based homepages. It uses VUE3 in the background.

### How to use
Just include the `index.html` in your homepage setup. You are free to rename the file.  
Add a csv-file to the public directory of your homepage (where your `index.html` resides). The csv should have the following format:  

    id;title;location;start;end  
    1;Some event;Some location;20.05.2023;  
    2;Next event;new location;20.05.2023 14:00;  
    3;one more event;other lcoation;20.05.2023;20.05.2023  
    4;new event;next location;20.05.2023 14:00;20.05.2023 23:00  
  
1. This line will create an event starting at 18:00h and ending two hours later.  
2. This one will create an event starting at the givven time and adding two hours for the end time.
3. Here the event will start at 18:00h and end at 20:00h.
4. This event will be created with the given times.

Feel free to edit the files 
