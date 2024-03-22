# Notes 2023

- The course was run in WiSe2023 with 6 students (5 oceanography and 1 geography).  2 of the students were about to do the Seepraktikum.  4 students had already done the Seepraktikum.

- Students were well-motivated.  We were somewhat flexible with necessary absences by the students, and it didn't appear to detract from the overall experience (no student missed more than 1.5 days of the course).

- Time was insufficient.  In the end, because we added an extra 1.5 lab days, the time allocated for analysis and producing the reports was not adequate, and this is apparent in the quality (detail and polish) of the reports.  With additional time, it may have been possible to go into a little more detailed analysis of the results.  However, the course as it occurred accomplished several aims.  The challenge of measuring salinity was impressed upon the students, as was the difficulty of getting clean results when the accuracy requirements are so high and the instruments so sensitive.  Students asked very good questions and even more so as the course progressed.  They were responsible and could be relied upon to assist each other; but needed occasional reminders about safety equipment (life vests) while carrying out the field experiment.

- Getting started with Python and Git took a couple hours.  Plan for this.  We used 2 hours on Wednesday afternoon of the first week, after the salinometry work.  This involved troubleshooting people's installations of conda/anaconda in order to install packages like `xarray` and `gsw`.  With Git, it was walking people through adding a personal access token in order to operate with GitHub on their personal computer.


## Lab experiments

- **Keeping vats well-mixed**. The trickiest part here appears to be keeping the salinity well-mixed.  Even with a couple aquarium pumps in each bin of water (about 30 x 70 cm), jostling the equipment in the tank led to salinity variations.  

    - Ideas to try: Smaller tanks, holding the instruments vertically
    - Ideas to try: Use a tall tank and build stratification.  See how stable it is

- **Getting the right salinity**.  We used pool salt for the experiments, but for whatever reason, even with carefully measuring water in 2L graduated cylinders and weighing the salt to be added, the resultant salinity of the water was about 1.5 salinity units too high.

    - Ideas to try: Table salt, marine salt, 
    - Ideas to try: Instead of relying only on the calculation (weight salt and measuring water volume) could instead do the rough calculation (S = M_s/(M_w+M_s)) and then adjust the salinity by adding salt/water and using real-time measurements of salinity until the desired salinity is reached.
    
    
- **Repeating experiments.** The students provided some feedback partway through that it would be nice to be able to re-run the experiments to get some cleaner results.  Rather than wait for the following year, they did these the next week.  On the second time around, they were *very* careful in measuring water volumes (and found that the lines indicating volume on the vats were off by at least several hundred milliliters) by using graduated cylinders (500ml and then found 2L in a lab upstairs to go faster - they needed 42L) and weighing salt (in two batches, 1kg and 500g, on a scale rated to 1200g.  We did not test whether the scale was well calibrated).  They also left instruments measuring overnight and found that the salinity in the tank adjusted more quickly (increased) over about 7 hours and then slowly increased for another 10 hours until the experiment was disturbed the next morning.  The temperature continued to increase overnight (over 17 hours).  They also mixed one batch of 42L salt water then divided the batch the following morning.  However, the water in the second tank (poured to from the first tank) was saltier.

    - Ideas to try: Use heating/cooling plates to control the temperature
    - Ideas to try: With oil and water, see how density stratification affects what is poured from one tank to another

- **Moving instruments carefully.** The CTDs used are very sensitive.  *How* the CTD is moved from one tank to another can affect the measurement, either by disturbing the stratification or circulation, or introducing airbubbles.  (The vertical tank idea above could help with air bubbles.)

- **Logsheets.** Possibly provide the students with logsheets with columns for time (UTC), notes/observations, initials for the people doing things, other?  

    - Ideas for next time: Ask the students to append scans of their logsheets as appendices for the reports.


## Field experiment

We went to Cuxhaven which is about 2 hours from Hamburg Hbf by train, and a little longer by car.  We needed the car in order to bring the equipment though with slightly less equipment it could be possible all by train (e.g., one Sea & Sun CTD, one additional hand-held CTD like an RBR Concerto - but this could be optional), a bucket, some rope and tape, weights to help the instruments sink, a laptop or two, life vests, refractometer, knife for cutting tape/rope, UTC watch and clipboard(s) for logsheets, cables for equipment and serial-to-USB, cable ties, small shackles, measuring tape, allen keys.  Of these the heavier items are the rope, the CTD, weights and laptops, and the bulkier items are the bucket and cables.

- **What worked well (location)**: The dock (Alte Liebe) had a covered area, was partially sheltered from wind, a metal railing behind the wooden railing which was good for tying things off, some benches, a trash bin and nearby cafe (opened at 9am) and public toilets (pay, was open by the end of the day--unclear at what time they opened otherwise).  It was near the train station (20 minute walk) and near a public parking lot (€10/day).  We used a small car to transport the equipment and two instructors, and two trolleys (one from ikea) to move equipment from the car to the dock (where there was a handicapped ramp in addition to the stairs).  

- **What worked well (water access)**: Water access was good, and water was deep enough (about 5 m at low, directly below the dock), the dock was about 4 m above the water level.  The dock railing was above the human center of mass which was good for people-safety.  (Lifevests are still recommended as a precaution, but also since it was a useful indicator to passersby of who was working with the equipment and of whom they could ask questions).  

- **Caution (transport)**: The drive is longish (2.5 hours) and traffic was good but there were some farm vehicles along the way.  There were also quite a few road closures and diversions between Hamburg and Buxtehude.  In the end, the students arrived at the dock around 8:20 and the equipment (and instructors) at 9:00.  The morning was cold (<10 degrees) so it was not a pleasant wait for them.

- **Small caution (gaps between boards)**: The dock was wooden so there were slatted gaps between boards.  It would have been possible to lose equipment between the slats.

- **What worked well (salinity)**: Measured salinities were about 7-12 which was good - much lower and there wouldn't be much of a signal.  Tidal variations were noted.

- **Caution (water depth)**: The students started sampling around 10am local (3 hours before low) which meant that the water level would decrease from the start.  But additionally, during the ebb tide, there were fairly strong currents towards offshore which strongly angled (about 30degrees) the rope used to measure water depth and the rope with sensors attached.  We had only brought one 2kg weight for measuring water depth, and this wasn't heavy enough for the weight to go straight down.  The strong currents also meant that the Sea & Sun CTD would not sink.  We used the bar from the unused microCAT as a weight on the Sea&Sun, which had the added benefit of providing an indicator (which could be felt by the student lowering the rope) of when the CTD (or the end of the bar attached to the CTD) reached the bottom.

- **Small caution (local eddies):** The students used the metal railing to tie off ropes (useful) but it meant that at flood, there were eddies being shed from the corner of the dock as the water came in.  This possibly affected measurements, but unclear.  Might be better to tie the equipment at the corner of the dock.

- **What worked well (profiling):** The Sea & Sun CTD was used for profiles every 30 minutes, which showed stratification during flood.  In between profiles, it was tied off to be near the surface of the water to provide a time series.  This was an added bonus since the students weren't able to tie two microcats at the right depths to make a "dangling" mooring.

- **Tips on timing (tides):** The data were interesting especially with having a low-tide in the middle of the record (high might have been interesting also, but ebb-only or flood-only would've been less likely to be interesting).  During flood, there was noticable stratification with saltwater coming in at depth (from the 30-minute profiles) and freshwater at the surface.  Differences between profiles were large, so possibly a more frequent interval would've been useful.