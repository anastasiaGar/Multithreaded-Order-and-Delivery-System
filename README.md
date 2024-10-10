# Multithreaded Pizza Order and Delivery System

This project implements a pizza ordering and delivery system using POSIX threads. The system simulates the process of handling multiple customer orders concurrently while synchronizing the availability of resources such as ovens, chefs, packing staff, and delivery workers. Mutexes and condition variables are used to ensure proper synchronization, avoiding conflicts between threads as they access shared resources.

Features
Multithreaded Simulation: Each customer is represented as a thread, and the system processes multiple orders simultaneously.
Resource Management with Mutexes and Condition Variables: The system efficiently handles synchronization of resources (e.g., ovens, staff) using POSIX mutexes and condition variables.
Order Status Tracking: Logs the time taken for each order from customer arrival to preparation and delivery completion.
Payment Simulation: Each order has a probability of payment failure, and unsuccessful payments halt further processing for that order.
Statistics Collection: Computes and prints the average and maximum time for customer service, including preparation, waiting, and delivery times.
