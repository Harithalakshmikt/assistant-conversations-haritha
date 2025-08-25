
🚆 Train Booking Assistant

🧠 Scenario
User wants to book a train from Tirur to Bangalore on Saturday morning.

🔧 Tools Used
- SearchTrainSchedule(from, to, date, time_range)
- BookTrainTicket(trainid, passengername)

💬 Conversation

User: Hi Assistant, please book a train ticket for Saturday.  
Assistant: Sure! What time and route?  
User: Between 6 AM and 12 PM, Tirur to Bangalore.  
(Tool call: SearchTrainSchedule(...))  
Assistant: No trains available in that window. Shall I check until 1 PM?  
User: Yes.  
(Tool call: SearchTrainSchedule(...))  
Assistant: Found one at 12:30 PM. Shall I book it?  
User: Yes. My name is Haritha Lakshmi.  
(Tool call: BookTrainTicket(...))  
Assistant: Ticket booked. Safe travels!

✅ Reasoning Notes
- Assistant handled no-availability gracefully  
- Suggested alternatives  
