---
lab:
    title: 'Lab 5.2: Schedule Items in Dynamics 365 Field Service'
    module: 'Module 5: Learn the Fundamentals of Dynamics 365 Field Service'
---

Module 5: Learn the Fundamentals of Dynamics 365 Field Service
========================

## Practice Lab 5.2 - Schedule Items in Dynamics 365 Field Service

## Lab Setup

  - **Estimated Time**: 20 minutes

  **Note:** The Booking Requirements pane cannot be opened in Internet Explorer. Please use Microsoft Edge or Google Chrome to complete this exercise.
  
## Instructions

1. If it is not open already, open the **Dynamics 365 Field Service** application.

2. Using the navigation on the left, select **Work Orders**.

3. On the **Command Bar**, select the **New** button to create a new Work Order.

4. Complete the Work Order details as follows:

	- Service Account: Adatum Corporation

	- Primary Incident Type: MRI Scanner down

	- Price List: US Bill Rates

	- Work Order Type: Select Service call from the look up

	- Taxable: No

5. Select **Save** to save your changes and stay on the newly created record.

6. On the **Command Bar** of the **Work Order**, select the **Book** button. This will open the **Schedule Assistant**.

7. You should be presented with options for scheduling the item. Select the **Ryan Brim** record.

8. In the **Create Resource Booking** window, set the **Start Time** to the **Top of the next hour**.

9. Set the **End Time** to 2.5 hours after that.

10. Select the **Book &amp; Exit** button to book the item and leave the scheduling window.

11. Once back on the Work Order click the **Save and Close** button from the **Command Bar**.

12. Using the left navigation, select **Schedule Board**.

13. At the bottom of the screen in the requirements panel, select **Unscheduled Work Orders**.

14. Select the **Adventure Works** Work Order you created earlier and use the work order number you wrote down. From the options that appear select **Find Availability**.

15. This will open the **Schedule Assistant**.

16. You should be presented with options for scheduling the item. Select the Bob Kozak record.

17. In the **Create Resource Booking** window, set the **Start Time** to the **Top of the next hour**.

18. Set the **End Time** to 2.5 hours after that.

19. Select the **Book &amp; Exit** button to book the item and leave the scheduling window.

20. At times, you may need to reschedule a work order based on technician conflicts or other items. This can be easily done by dispatchers leveraging the schedule board.

21. Click in Search resources box on the schedule board (Located right above the resource name column), enter Ryan and locate the work order that is scheduled for Ryan later today.

22. Right-click on the work order, and from the menu that appears, select **Substitute Resource**, select the **Find Substitution** button.
