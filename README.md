# Alert System

This code is a customizable alert system for forex trading platforms. It allows users to create alerts at specific price levels and customize the visual properties of the alert line. The code also includes functions for managing and activating alerts, as well as sending alert notifications via email or SMS.

## Usage

To use this alert system, follow these steps:

1. Set the desired alert options by calling the `SetAlertOptions` function. This function allows you to customize the line color, style, width, and text of the alert.

2. Create an alert by calling the `CreateAlert` function. Pass the desired price level and symbol as parameters. This function will create a horizontal line on the chart at the specified price level, using the previously set alert options.

3. Check if the alert is triggered by calling the `IsAlertTriggered` function. Pass the price level as a parameter. This function will return `true` if the alert is triggered, and `false` otherwise.

4. If the alert is triggered, send a notification by calling the `SendAlertNotification` function. Pass the desired notification method ('email' or 'sms') as a parameter. Currently, only email notifications are implemented in the code. For SMS notifications, you will need to integrate with your preferred SMS gateway.

5. Manage the alert by calling the `ManageAlert` function. Pass the desired action ('edit', 'delete', 'enable', or 'disable') as a parameter. This function allows you to modify or delete the alert line, as well as enable or disable its visibility on the chart.

## Customization

The alert system can be customized by modifying the global variables at the beginning of the code. You can change the default line color, style, width, and text by assigning new values to the respective variables.

## Product Description

Alert System is a powerful tool for enhancing forex trading with customizable alerts. With this system, traders can set personalized alerts at specific price levels, allowing them to stay informed about market movements and take timely actions.

The alert system offers a range of customization options, including the ability to choose the line color, style, width, and text for each alert. This allows traders to tailor the alerts to their preferences and trading strategies.

When an alert is triggered, the system can send notifications via email or SMS. Email notifications are already integrated into the code, while SMS notifications can be implemented by connecting to a preferred SMS gateway.

Please note that ForexRobotEasy is not the official developer of this product. We are showcasing a sample code that demonstrates how the product can work. To find the official developer and access detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/alert-system-review-enhance-forex-trading-with-customizable-alerts/). For further customization and support, we recommend contacting the official developer through the MQL5 platform.
