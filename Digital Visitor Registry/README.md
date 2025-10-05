
# Digital Visitor Registry

The Digital Visitor Registry is designed to simplify and digitize the process of handling visitors at institutions. Instead of relying on manual logbooks and tedious paperwork, DVR allows for a seamless digital check-in experience. It not only tracks every individual entering the campus but also records their duration of stay. Traditional methods, where guards manually log visitor details, are inefficient and hard to reconcile. DVR eliminates these issues, making the visitor entry, exit, and tracking process more efficient and user-friendly.

<br>

**Built With:** MERN Stack (MongoDB, Express.js, React, Node.js) <br>

**Key Features:**

1. **Visitor Registration**

   > Visitors can easily register through either **WhatsApp** or the website. The interface is designed for simplicity and ease of use, allowing guests to select their preferred time slots. On WhatsApp, users go through a quick 4-step registration process that begins with sending a simple "Hi." Once registered, they receive a **Gate Pass** directly via WhatsApp, which is later used at the entry gate where the guard scans the QR code for verification.

2. **User & Admin Profile Pages**

   > Both visitors and administrators have access to profile pages where they can update personal details and reset passwords. Admin users also have access to an HTML editor, allowing them to customize homepage content and display styled information or notices dynamically.

3. **WhatsApp Message Configuration**

   > The **WhatsApp Settings** page allows admins to customize automated message replies sent by the chatbot during visitor registration. Getting started is simple—just scan the WhatsApp Web QR code to activate the system. From there, admins can tailor response messages to improve communication and engagement.

4. **QR Code Scanning for Entry & Exit (Guard Access)**

   > Guards are given special login access, enabling them to scan visitor QR codes using their phone camera or upload an image when using a computer. Upon entry, scanning the code initiates a visit timer. At exit, a second scan ends the session. This ensures accurate logging of visit durations with minimal effort from the guard.

5. **Admin Panel & Real-Time Dashboard**

   > The admin dashboard provides a live overview of visitor and guard activity. As visitors are checked in at various gates, the data updates in real time. Admins can monitor all ongoing and past visits, including current visitor durations which are color-coded to highlight extended stays—helping identify potential security concerns. The admin panel also allows for adding or removing guards and managing the complete database of users and visitors.
