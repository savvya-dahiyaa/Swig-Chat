# Swig-Chat
Swig-Chat is an intelligent customer support chatbot designed to enhance user experience on Swiggy by providing real-time order assistance, empathetic responses, and proactive issue resolution.

Swig-Chat aims to replicate a real-world food delivery support system by combining structured order data with realistic customer scenarios.
It intelligently understands user queries, identifies the order context, and responds using tone-based messages, whether helpful, apologetic, or delightful depending on the situation. 
It uses a detailed order dataset with real-life fields (order ID, status, ETA, payment method, delay reasons, complaints, Instamart items, etc.) and a scenario dataset with 70+ situations (angry user, missing item, delays, refunds, cancellations, Instamart issues, etc.)
Based on the user’s message and emotion, the chatbot picks the correct scenario and generates empathetic, contextual, and brand-aligned responses.

<img width="1389" height="613" alt="image" src="https://github.com/user-attachments/assets/1ba76203-29ed-4f71-8cc5-fbe248a351b5" />

How the Bot Works:

User sends a message →
“Where is my order 1012?”

Bot detects intent (order status, refund, complaint, emotion)

Bot fetches order details from the Order Dataset
→ Order 1012 = Delayed due to traffic

Bot matches scenario from Scenario Dataset
→ Scenario = “Order delayed — traffic congestion”

Bot adapts tone based on sentiment
→ User frustrated → use apologetic/empathetic tone

Bot replies using the correct message template

Adds: updated ETA, reason, and optional promo code

Offers buttons like: Track Order / Talk to Agent

This creates human-like, accurate, and relevant support responses.
