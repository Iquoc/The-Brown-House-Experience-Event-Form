# The-Brown-House-Experience-Event-Form

<b>This is a full-stack website application developed by a team of Computer Science Undergraduates at DePaul University for a client in the Senior Capstone course.  Because the application was handed off to the client, complete files and structures have been omitted.  <br>  I worked on the backend team, mostly involved in: database connect/read/write; waitlist functionality; waitlist flow chart; and, architecture design.</b>

<h2> Main File:</h2>

<b>Here are examples of using routing in React.js, efficient method calling, code commenting, initializing database connection, and appropriate handling of commands between separate Python files.</b>

<img src="/main/main_database_connect.jpg" alt="db_connect" style="float: left; margin-right: 15px; margin-top: 10px;" />
<b>The above code is one of the initial calls in the Main File and is responsible for initializing and establishing the database connection.  The singleton/instance of the database connection allows for one connection call and reuse without having to waste resources on establishing the same connection each time the web application needs to read/write to database.</b>
<img src="/main/create_form.jpg" alt="create_form" style="float: left; margin-right: 15px; margin-top: 10px;" />
<b>The above code uses routing in React.js, comments to organize the method calls and its purpose, appropriate variable naming conventions, and handling of commands between separate Python files.</b>
<br>
![delete_form!](/main/delete_form.jpg)
<b>The above code uses routing in React.js, appropriate variable naming conventions, and handling of commands between separate Python files.</b>
<br>
![delete_participant!](/main/delete_participant.jpg)
<b>The above code uses routing in React.js, appropriate variable naming conventions, and handling of commands between separate Python files.</b>
<br>
![ext_year!](/main/extrapolate_year.jpg)
<b>The above code uses appropriate variable naming conventions, and efficient method organization.</b>
<br>
![wl!](/main/waitlist.jpg)
<b>The above code uses comments to organize the method calls and its purpose, appropriate variable naming conventions, and handling of commands between separate Python files.<br></b>

<h2> Database File:</h2>

<b>Due to the sensitive nature of database connection and read/writing, I can only provide generic examples.  This is a draft of using MongoDB database and collection calls and CSV formatting for exportation.</b>

![export_CSV!](/database/export_to_csv.jpg)

<h2> Conceptual Diagrams:</h2>

<img src="/conceptual-diagrams/TBHE-waitlist-final.drawio.png" alt="waitlist_flow" style="float: left; margin-right: 15px; margin-top: 10px;" />
<b> Above is the waitlist flowchart to communicate the functionality of waitlisting participants in regards to payment and registration.</b>

<img src="/conceptual-diagrams/tbhe-events-architecture.jpg" alt="architecture" style="float: left; margin-right: 15px; margin-top: 10px;" />
<b> Above is the architecture diagram used in the early stages of the web development.  I worked closely with the Software Architecture, Serhat Cingilli, to research and assess the appropriate tools and frameworks for our clients needs.  For example, our client asked for a way to integrate secure online payments in the web application.  Prior to our group, the professor had cautioned the class against using payment in our softwares because it had not been previously done and could lead to scope creep, vulnerable software, and other difficulties that the professor could not help with if they arrise.  In my research, I came across the Stripe API.  I had previous experiences using web requests and made the decision to investigate the implementation with Max Kenner, ultimately allowing us to integrate a payment system securely.  This is significant in proving payment functionality in the DePaul University Computer Science Senior Capstone course.</b>
<br>

<b>One of my responsibilities as part of the backend team is to connect the database to the backend.  Here is a draft of the schema I designed and presented to the team.  This helped conceptualize and communicate the structure of the database so that we can work coherently on the same project.</b>
- [Database Schema Draft](https://github.com/Iquoc/The-Brown-House-Experience-Event-Form/blob/main/conceptual-diagrams/schema-drafts.txt)

<h2> Credits:</h2>

<b>Of course, this project would not have been possible without my hardworking and talented team members.  Below, I have credited them with their respective roles.<br></b>

- Aimun Anwer: Product Owner, Frontend
- Anh Luong: Scrum Master, Frontend
- Ayesha Khan: Frontend
- Hamza Mirza: Frontend
- Max Kenner: Backend
- Serhat Cingilli: Software Architect, Backend
- Sophie Kostovski: Webmaster, Backend
- Tatiana Goodman: Documentation Lead, Backend
