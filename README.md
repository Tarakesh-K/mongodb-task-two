Task - 1

db.companyDrives.find();


Task - 2

db.companyDrives.find();

Task - 3

db.companyDrives.find();


Task - 4

db.users.find({}, ["codekataProblemsSolved"]);

Task - 5

db.mentors.find({"mentees": {$gt: 15}});

Task - 6

db.users.find( { "overallAttendance": {"date": "15-10-2022 to 31-10-2022", "AttendancePercentage" : 100, "TaskCompletion" : 100} } );
