𝐓𝐚𝐬𝐤 𝟏: 𝐃𝐚𝐭𝐚 𝐂𝐥𝐞𝐚𝐧𝐢𝐧𝐠 𝐚𝐧𝐝 𝐏𝐫𝐞𝐩𝐫𝐨𝐜𝐞𝐬𝐬𝐢𝐧𝐠
 
 📌𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞
 To clean and prepare the Medical Appointment No-Shows dataset by addressing missing values, duplicate records, text inconsistencies, and encoding issues using Microsoft Excel.
 🧹𝐂𝐥𝐞𝐚𝐧𝐢𝐧𝐠 𝐒𝐭𝐞𝐩𝐬 (𝐄𝐱𝐜𝐞𝐥 𝐎𝐧𝐥𝐲)
 𝟏.𝐇𝐚𝐧𝐝𝐥𝐞𝐝 𝐌𝐢𝐬𝐬𝐢𝐧𝐠 𝐕𝐚𝐥𝐮𝐞𝐬:Identified missing or blank cells using filters and Go To Special → Blanks. Replaced missing values with appropriate placeholders (e.g., "Unknown").
 𝟐.𝐑𝐞𝐦𝐨𝐯𝐞𝐝 𝐃𝐮𝐩𝐥𝐢𝐜𝐚𝐭𝐞𝐬:Used Excel’s Remove Duplicates feature to eliminate repeated rows based on unique identifiers.
 𝟑.𝐅𝐢𝐱𝐞𝐝 𝐄𝐧𝐜𝐨𝐝𝐢𝐧𝐠 𝐈𝐬𝐬𝐮𝐞𝐬:Resolved character encoding problems in the Neighbourhood column(e.g., SÃƒO → SÃO) using UTF-8 re-import or manual correction.
 𝟒.𝐂𝐨𝐫𝐫𝐞𝐜𝐭𝐞𝐝 𝐓𝐲𝐩𝐨𝐬 𝐚𝐧𝐝 𝐅𝐨𝐫𝐦𝐚𝐭𝐭𝐢𝐧𝐠 𝐢𝐧 𝐍𝐞𝐢𝐠𝐡𝐛𝐨𝐮𝐫𝐡𝐨𝐨𝐝𝐬:Standardized spelling, removed special characters, and ensured consistency in names.
 𝟓.𝐒𝐭𝐚𝐧𝐝𝐚𝐫𝐝𝐢𝐳𝐞𝐝 𝐓𝐞𝐱𝐭 𝐅𝐢𝐞𝐥𝐝𝐬:Applied Excel functions like TRIM(), UPPER(), and PROPER() to remove extra spaces and format text uniformly.
 𝟔.𝐅𝐨𝐫𝐦𝐚𝐭𝐭𝐞𝐝 𝐃𝐚𝐭𝐞 𝐂𝐨𝐥𝐮𝐦𝐧𝐬:Converted ScheduledDay and AppointmentDay to a consistent dd-mm-yyyy format.
 𝟕.𝐕𝐞𝐫𝐢𝐟𝐢𝐞𝐝 𝐚𝐧𝐝 𝐂𝐨𝐫𝐫𝐞𝐜𝐭𝐞𝐝 𝐃𝐚𝐭𝐚 𝐓𝐲𝐩𝐞𝐬:Ensured numeric fields (e.g., Age) and binary indicators (e.g., Hypertension, Diabetes) had the correct data types.
 𝟖.𝐑𝐞𝐧𝐚𝐦𝐞𝐝 𝐂𝐨𝐥𝐮𝐦𝐧 𝐇𝐞𝐚𝐝𝐞𝐫𝐬:Cleaned and renamed column titles to be lowercase, readable, and consistent(e.g., No-show → no_show, ScheduledDay → scheduled_day).
 
 🧰𝐓𝐨𝐨𝐥𝐬 𝐔𝐬𝐞𝐝
 Microsoft Excel for data exploration, cleaning, and formatting
 
 📂𝐅𝐨𝐥𝐝𝐞𝐫 𝐂𝐨𝐧𝐭𝐞𝐧𝐭𝐬
 Task-1 → Summary of Data cleaning
 cleaned_data.png → Excel-cleaned version of the dataset
 README.md → Summary of the data cleaning process and steps
 
 ✅𝐎𝐮𝐭𝐩𝐮𝐭
 A clean dataset: ⁠medical_appointments_cleaned.csv ⁠ ready for analysis or visualization.
