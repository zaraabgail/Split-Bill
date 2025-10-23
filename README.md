# Split-Bill

A Streamlit web app for calculating and splitting restaurant bills fairly among multiple people.  
Supports PPN, service charge, and percentage-based discounts that affect the tax base.

## Features
- Add items with unit price and quantity  
- Assign each item to specific people  
- Apply VAT (PPN) and service charge percentages  
- Apply discount (%) to subtotal before tax  
- Choose tax base: subtotal or subtotal + service  
- Rounding options (none, nearest Rp100, or Rp1.000)  
- Automatically hides results until data is entered  
- Displays the highest spender only if there is a single top payer

## How it Works
1. **Subtotal** = sum of all items (price × quantity)  
2. **Discount** = percentage of subtotal  
3. **Discounted subtotal** = subtotal − discount  
4. **Service** = percentage of subtotal  
5. **Tax (PPN)** = percentage of discounted subtotal (or discounted subtotal + service)  
6. **Grand Total** = discounted subtotal + service + tax  
7. Each person pays based on assigned items and proportional charges

## Link
https://split-bill-frdkuzbl4hbfygevcck8wx.streamlit.app/
