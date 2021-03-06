# caroolive-app
- Driver service client app integrating OBD2 diagnostics and dashcam functions
- The commercial OBD library and video blackbox library of CaroO Pro Driving Recorder included 
- Cloud server and connection only for testing connected car services 

# OBD2 related features
- OBD library for connecting bluetooth OBD devices (ELM327 compatible) and reading PID data
- OBD library for add-on features such as ignition detection, fuel-cut detection, fuel eco estimation, etc. 
- OBD raw data collection for external data processing
- Read and clear DTC codes as well as OBD PIDs
- Read VIN code 

<br>
<img src="/screenshots/driving_mode.png" width="600px">
<img src="/screenshots/driving_details.png" width="600px">
<br>


# Dashcam video
- Video processing library for recording, splitting, partial-extracting video
- Two types of video recording mode: file recording and continuous recording
- Emergency detection and sharing emergency situation by phone-call, SMS and YouTube
- Integrating with OBD data: saving trip data to SMI formatted files
- Dedicated video player combining video, driving data and map
  
<br>
<img src="/screenshots/dashcam.png" width="600px">
<img src="/screenshots/video_play.png" width="600px">
<br>
  
  
# Connected car service (beta)
- Google/Facebook authentication and log-in 
- Uploading OBD data for further analysis and statistics
- Trip statistics, fuel economy, driving pattern analysis
- Car diagnostics history and car status analysis
- Additional features such as driving point, level and ranking for Korea/Japan users (UTC+09:00 time zone)
- [Beta service link](http://www.carooplus.com:9801)

<br>
<img src="/screenshots/service_screens.png" width="640px">
<br>

  
# Credits
- [Caldroid](https://github.com/roomorama/Caldroid)

# License
(c) 2017 Pokevian Inc.

CarooLive is free software distributed under the Apache 2.0 license. 

# Contacts
Contact us at support@pokevian.com if you have questions or suggestions.  
