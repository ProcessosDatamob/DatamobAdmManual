---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Messages and Commads

The purpose of this system screen is to enable the user to send messages and commands to all the company's devices, to one or more groups or to one or more users of specific devices. Messages and commands are sent via PUSH and do not generate SMS consumption.

To send one or more messages, they are placed in a queue where they are grouped and sent to the device every minute. Depending on the volume of messages to be sent, it may take a while to send them to the device, but no longer than 2 minutes for the messages to leave the queue and be sent.

The messages that can be sent are free text and can contain up to 160 characters.

The commands that can be sent are not available on the Portal, as they perform actions that can affect the operation of the device or application.

Some of the special commands are:

* Logon - Enables logging by the application.&#x20;
* Logoff - Disables logging by the application.

{% hint style="info" %}
**Note**&#x20;

To restart the services in case of communication loss of the application, click on “New Message”, send the message “start\_services” to the affected devices. When the application receives the push with the command, it will initialize the application's processes, activate the application's alarms, and send the relevant application information, including Device Info, Usage, Site, and SMS.
{% endhint %}

When receiving a command, the application will not display the text of the command sent.

To find out how to send messages and commands, follow the steps described in this section.

1. Click on the "Messages" menu to access the screen.
2. To send messages and commands, click on the "New Message" button.

<figure><img src="../../../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

3. You can send messages to all the company's devices, to one or more groups or to one or more users of specific devices.

You can also send the same message or command to companies, groups and device users simultaneously. To do this, simply fill in the fields and make the combination you want.

{% hint style="info" %}
**NOTE**

If a device is entered in two fields (e.g. group and user), it will receive two messages or commands.
{% endhint %}

4. If you want to exclude the company, group or device user from the selection, click on the "x" next to the selected item.
5. Type in the message or command.
6. Click on the "Send" button to place the message or command in the send queue.
7. When you place the message or command in the send queue, the system will display the command or message in the send report.

<figure><img src="../../../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

8. If you want to select a specific period, you can select the dates in the Filter field;
9. After selecting the dates, click on Search. If you want to search without selecting dates, just click on Search;
10. To export the application report, click on "Excel".
11. To copy the information from the applications report, click on "Copy".
12. If you want to view a specific message or command, enter the text in the "Search" field.
13. To sort the information displayed, click on the heading of the "date" column.
14. To find out more, click on "..." and choose "View Message".
15. To view a larger number of locations per page, select the number at the bottom of the page, as shown below.
16. Use the navigation field to view the locations of the other pages in the report.
