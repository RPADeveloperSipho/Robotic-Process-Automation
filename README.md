# Robotic-Process-Automation
RPA is one of the newest tech in the world. I have created this repository for all my assignments that am working on. 

XML file with name “Config_App” in C:\RPAConfig folder with below format.
Read each node and store the node values in respective variables in AAE Client.

- XML command suports sessions, node editing and XPath expression - everything is based on tree structure of an XML document.
- It have 8 sub commands
  - Start XML - specifies session and data source
  - End XML - closing the opened session
  - Insert Node - specifies node name and value. This is based on XPath Expression(navigate through elements and attributes in an XML)
  - Delete Node/Attribute - deleting the node or attribute - specofied by XPath
  - Validate XML Document - vakidates session using XML schema files
  - Get Node(s) - Retrieves the values(s) of a single or multiple nodes
    -When getting multiple nodes the can be used with *Loop
  - Session data - saves the session data to a variable
  -Execute XPath Function - results are stored in a variable
  

  
