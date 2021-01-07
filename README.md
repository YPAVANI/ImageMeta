This project requires contains the following:

1.       Developed an image metadata management system with a web application as the front end. An image has a number of metadata characteristics such as ISO settings, resolution, pixel depth, exposure, camera settings, camera type and so on. Each image might contain a different mix of fields depending on what features the camera supports. A cell phone might add GPS coordinates as metadata, while another might add more detailed flash information. This means that a proper schema is difficult to establish, and hence a NoSQL document based database such as MongoDB is a suitable choice for storing this information.

a.       The web application will have facility for both admin as well as user login

b.      The backend database is a MongoDB server

c.       The web application will support efficient searching of the stored images based on different metadata features

2.       The web application and the database server will be in different containers and must communicate with suitable mechanisms

a.       The web application will be publicly accessible with a default guest user, with username and password set as “guest”

b.      Note that both containers can be connected using SSH for verification. (Ensures a default username and password “root”)

 
