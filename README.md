USE Daas_STAGE --- You don't need to square bracket, but they don't hurt

DROP TABLE ADO_Extract

CREATE TABLE sgr.ADO_Extract(
ID INT,
Title NVARCHAR(255), 
AssignedTo NVARCHAR(255),
[State] NVARCHAR(60),
AreaPath NVARCHAR(255),
Tags NVARCHAR(255)
);

INSERT INTO ADO_Extract
(
-- id column value is auto generated
Id, Title, AssignedTo, State, AreaPath, Tags
)
Values
(
'Feature', 'Design Week Preparation - Wave 2,'Done', 'Core Team Program', 'Secure the Digital Transformation\ISP\AST', 'Secure the Digital Transformation')





<!---
NEABRAHAM/NEABRAHAM is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
