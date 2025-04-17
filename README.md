# load balancer

security grouop---operate instance level, associated with instance control acess to instance, stateful-means return traffic allowed,

network acli--- operate subnet level, contorl which traffic is allowed that subnet, stateless--means return traffic will be allowed by crating rule only





 🔐 **Security Group**:
- Like a bouncer at the door of your room (EC2 instance).
- Controls who can come in and go out of that room.
- Remembers who came in, so lets them go out automatically.
- Only allows traffic – doesn’t block anything unless you say so.
- Attached directly to the EC2 instance.



 🚧 **Network ACL (NACL)**:
- Like a security gate for your whole neighborhood (subnet).
- Checks all traffic going in and out of the area.
- Does NOT remember** who came in – you have to allow return traffic separately.
- Can allow or block traffic.
- Works at the subnet level, not on individual instance.

OSI MODEL--
🔹 **7 Layers of the OSI Model (from top to bottom):**


- **Application** – You write the message (Gmail, WhatsApp).
- **Presentation** – You choose the language and format it.
- **Session** – You start a conversation.
- **Transport** – You ensure the letter gets delivered fully.
- **Network** – Post office decides the route.
- **Data Link** – Postman ensures it gets to your house.
- **Physical** – The actual delivery truck, roads, mailbox

 network load balanceris very costly 






