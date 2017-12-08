# Final Writeup
In component 1, when we opened the dataset, we realized that we had to analyze data which has three dimensions: the latitude, the longitude and time. Also, we had to create three visualizations. Two of the visualizations are in two-dimensional form and the third visualization which contains the map is in a three-dimensional format.  We did the preprocessing of the data and we found that the time was in a different format, so we processed the time so that the time unit displayed was in usual time: Hours, minutes and seconds. To locate the stations using the available data, on a three-dimensional axis, we analyzed each plane along the time axis and then found the point where the latitude and longitude on that plane.  
  
The strength of our approach is that using the above techniques, we could plot out the stations which detect tectonic plate movements and we could visualize the positions on a map of the USA. From the visualization, we could then create a video which could help users understand patterns in the tectonic plate movement and create a visualization with which we could demonstrate the strength of the movement of the tectonic plates with respect to the change in the sequential pattern of up and down movements detected from the sensors.
  
The code of component 1 initially was running slowly, which we felt was a weakness even if we got the correct output. This was because we imported much more data at the same time to reduce coding time. This importing of a larger data set increased processing time. We had to modify the code significantly so that we could import lesser amount of data at a given time to improve the speed of execution of the code.
  
For the visualization on the website, we used JavaScript. In HTML it is easy to relocate the visualizations on the web page. JavaScript is good for simulation and D3 library in JavaScript displays the visualization in SVG format. Placing the SVG visual on the HTML webpage is a challenge. It took us some amount of troubleshooting to solve this issue. 
In component 3, we extracted data from the UFO sightings dataset. As per the requirements, we managed to write the codes and the get the correct outputs. The strength of our approach is that we made the code as modular as possible so that future users can develop unique codes from the codes we wrote. The weakness in our approach is regarding the use of bqplot. Getting the output using the bqplot was difficult because of limited amount information and documentation available about the bqplot compared to other data visualization library. The issues we faced was that the color was not changing when the drop-down menu was changed from a total number of sightings to total duration and vice versa and the graph was not changing. We solved the issues by troubleshooting the coding errors after execution of the code as well as looking for similar examples.
In component 4 we created the infographics using Canva. To create the infographics, we selected snippets from components 1, 2 and 3 and explained the snippets in a visual format using text, arrows, and ellipses.
  
To demonstrate our work, we made videos for component 1, component 2, component 3 and component 4 so that the people can get a better understanding of our video.
  
Based on discussions with the team members responsible for Components 1,3 and 4, the final write-up was made.

Each team member was assigned a designated task. The tasks of each team member is mentioned below:
1)	Bin Xu: Component 1 and component 2
2)	Danning Du: Component 3
3)	 Riku Iwanaga: Component 4
4)	Abhishek Wagh: Final writeup

Video description of component 2:
From the map, we can see that generally, the plate tectonic up and down movements are random. This random movement indicates less plate tectonic movement. But in certain instances when the plate tectonic movements are severe, THE RANDOM MOVEMENT CHANGES TO SEQUENTIAL PATTERN OF UP AND DOWN MOVEMENTS, EITHER FROM SOUTH TO NORTH OR FROM NORTH TO SOUTH. Once the severe plate tectonic movements stop, the sequential up and down movements of the plate tectonics again becomes a random movement.
The video initially shows random up and down movements. But from the 9th minute, we can see a shift in the pattern of movements. From the 13th minute, there is a clear sequential moving pattern of up and down movements from north to south. THE CLARITY OF THE MOVEMENT INDICATES THAT THE TECTONIC PLATE MOVEMENT IS ESPECIALLY SEVERE. After the 52nd minute, the plate movement becomes fully random. 
  
We can see that there are a few instances where there are sequential up and down movement patterns, but the patterns are not so clearly visible. This means that the plate tectonic movements are not that strong. But at 1 hour and 27 min and at 2 hours and 16 minutes, the movements become strong again for around 5 minutes and the sequential up and down motion starts but in a south to north direction. At 3 hours and 40 minutes, the movements become strong and the sequential up and down motion starts but in a north to south direction for around 10 minutes. The plate tectonic movements occurring at the 1 hour and 27 min, 2 hours and 16 minutes and at 3 hours and 40 minutes are strong but not as strong as the plate tectonic movement at the 13th minutes.
  
Thus, we can see the few instances in which there are severe plate tectonic events. This video provides a unique perspective of the Tohoku earthquake.

In the visualization for dynamic wave change, the waveform of the tectonic plate movement (or the shockwave) that is detected by each station can be seen. When we click any station on the map, we can see the dynamic wave change. We can see that in the event the shock is massive, the waveform changes color from green to red. When the shockwave becomes less, the waveform changes color from red to green. We observed some patterns on the dynamic wave change visualization: At the 23rd minute, the shockwave is massive due to change in color to red and amplitude. From the 30th minute, the massive shockwave lasts for a long time for around 22 minutes, but the massive shockwave is in short bursts during that time.

In the visualization for static wave change, when we click any station on the map, the waveform of the shockwave at that instant can be seen. The waveform will not change with time unlike the visualization for dynamic wave change.

From the above three mentioned visualizations, we can get a comprehensive idea about the nature of the Tohoku earthquake and it can help in further earthquake research. 




