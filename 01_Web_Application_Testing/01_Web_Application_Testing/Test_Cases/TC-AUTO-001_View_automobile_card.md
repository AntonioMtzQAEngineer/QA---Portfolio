🧪 Test Case: View Automobile Card Information

Test Case ID: TC-AUTO-001  
Title: Verify automobile card displays title and price correctly  
Priority: High  

📌 Preconditions:
- User is on the main automobile listing page
- At least one automobile is marked as "Reserved"

🧭 Test Steps:
1. Open the automobile listing page
2. Locate an automobile marked as "Reserved"
3. Observe the automobile card

✅ Expected Result:
- The automobile title is visible
- The automobile price is visible
- The "Reserved" overlay does not hide critical information

❌ Actual Result:
- The "Reserved" overlay hides the automobile title and price

---

🐞 **Related Bug**
- [BUG-001 – Automobile reserved overlay hides title and price](../Bug_Reports/BUG-001_Automobile_reserved_overlay_hides_title_and_price.md)
