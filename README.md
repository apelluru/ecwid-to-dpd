# ecwid-to-dpd

# Description:
The ecwid_to_dpd project is an automated solution designed to streamline the order fulfillment process between Ecwid (an e-commerce platform) and DPD (a shipping and logistics provider). Currently, orders placed on Ecwid need to be manually exported and processed in DPD to create shipments. This project automates the entire workflow, reducing manual effort and minimizing potential errors.

The Python-based application fetches new orders from Ecwid daily, formats the order details to match DPD's API requirements, and then submits the data to create a shipment. By automating the data exchange, the project significantly enhances efficiency and ensures that orders are processed for shipping with minimal delay.

# Key Features:
Daily Batch Processing: The application retrieves orders placed within the last 24 hours to capture all recent activity.
Data Transformation: Order details are formatted according to DPD’s specifications for seamless integration.
Error Logging: Tracks errors and logs successful or failed attempts, aiding in troubleshooting and ensuring accountability.
Local Execution: Designed to run locally without server dependency, making it cost-effective and easily manageable.

# Components:
Order Fetching: Connects to the Ecwid API to retrieve new orders.
Shipment Creation: Transforms and sends order data to DPD’s API to create shipments.
Logging: Generates logs to monitor the application’s daily operations and status.

# Project Goals:
To reduce the time and effort involved in manually exporting order data from Ecwid to DPD.
To improve data accuracy and reduce the likelihood of human error in the shipment creation process.
To provide a scalable and budget-friendly solution for daily order export and shipment processing.
