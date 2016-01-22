# Mobile-App-for-Thesis
This is the mobile application I created for my thesis, Offloading Mobile App Components to Conserve Constrictive Mobile Resources.
It is a two button app, that contains two intent services.
AppIntentService
The first intent service runs a random multipling matrices computation and returns the result to the Main Activity (Local Mode).
WebService
The second intent (Remote Mode) service opens a HTTP connection to a Servlet (see Java-Servlet-for-Thesis repository) which would run the same computation class in Local Mode. The second intent got the result from the servlet and send it to the Main Activity.  
Energy profiler (Trepn profiler) was used to measure the CPU, Memory and battery usage.
The values from profiler while the computation was run in Local and Remote were compared (using IBM SPSS) in order to find when it which mode used least battery power.  
