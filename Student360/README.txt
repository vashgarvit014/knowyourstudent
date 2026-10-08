STUDENT 360° — PIET, Department of CSE (Sections A, B, C) & CS-R (Section D)
==========================================================================

CONFIDENTIAL: this folder contains student names and results. Keep it within the department.

FOLDER CONTENTS
  index.html                 -> the portal. Double-click to open (Chrome or Edge recommended). No internet needed.
  data/student_data.js       -> processed data that index.html reads. Created by "Update data". Do not edit by hand.
  data/results/              -> put the "UG Degree Database" Excel files here (one file per batch).
  data/attendance/           -> put the attendance Excel files here (Digital Campus "Complete Attendance Details"
                                exports or the HOD attendance reports).

HOW TO OPEN
  1. Copy the whole Student360 folder (pen drive / laptop / shared drive). Keep index.html and the data folder together.
  2. Double-click index.html.

HOW TO UPDATE THE DATA (new result or new attendance)
  1. Copy the new Excel files into data/results or data/attendance. Remove old files you no longer want.
     (The portal detects the file type from its columns, so a file in the wrong sub-folder still works.)
  2. Open index.html -> click "Update data" (top bar).
  3. Chrome / Edge: click "Choose Student360 folder & update", select the Student360 folder, allow access.
     Check the summary (files read, students matched, name differences), then click "Save to data/student_data.js".
     Other browsers: click "Other browsers: read folder...", select the folder, click "Download student_data.js",
     then copy the downloaded file into Student360/data (replace the old one).
  4. Next time index.html opens, it shows the updated data.

  Matching: students are matched by Registration No.; names are compared and any differences are listed.
  If the same student appears in several attendance files, the newest and most detailed record is used.
  Students who appear only in an attendance file (e.g. a batch whose results file is not added yet) are added
  with attendance only.

WHAT IS AND IS NOT STORED
  Stored in data/student_data.js: Reg. No., University Roll No., name, section, status, semester-wise SGPA and
  backlogs, CGPA, attendance figures (%, present/total, RTU eligibility, debar risk, DECA/SODECA marks, 13-Nov projection).
  NOT stored: phone numbers, e-mails, addresses, parents' names, date of birth, remarks columns.
  Faculty notes typed in "Faculty Actions" are kept only while the tab is open.

REQUIRED COLUMNS
  Results file   : Reg. No., Name of Student, Section, Branch, Status, University Roll No., SEM-1 Marks ... SEM-8 Marks,
                   SEM-1 Backlogs ... SEM-8 Backlogs, CGPA  (same layout as the UG Degree Database sheets)
  Attendance file: a Reg. No. / Student Reg Number column and an Attendance % / Attendance Today / Attendance Percentage
                   column; Section (e.g. 5CS-A) or the Digital Campus "Batch Session ... Semester N" filter tells the semester.

-----------------------------------------------------------------------------------------------
HINDI/HINGLISH QUICK GUIDE
  • Kholna: Student360 folder mein index.html par double-click kijiye (Chrome/Edge best).
  • Naya data: nayi Excel files data/results (result) ya data/attendance (attendance) mein daaliye ->
    index.html kholiye -> "Update data" -> Student360 folder chuniye -> summary check kijiye -> "Save" dabaiye.
  • Folder hamesha poora copy kijiye — index.html aur data folder saath rehne chahiye.
  • Yeh folder confidential hai; department ke bahar share na karein.
