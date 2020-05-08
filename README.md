## QWQER Extension Documentation (OpenCart v3.x)

### Installation
1. Download extension [qwqer-opencart-v3.x.ocmod.zip](https://github.com/IPayDevTeam/QWQER-OpenCart-Extension-Documentation/raw/master/extensions/qwqer-opencart-v3.x.ocmod.zip)
2. Go to your store at page: **Extensions > Installer**
3. Upload and install extensions by clicking button **Upload**
4. Go to page: **Extensions > Modifications** and click button **Refresh**
5. Go to page: **Extensions > Extensions > Modules** and click **Install** beside QWQER Delivery

### Configuration / Activation
1. Go to page: **Extensions > Extensions > Modules** and click **Edit** beside QWQER Delivery
2. Type your QWQER merchant's credentials (**login** and **password**)
3. Type **your store's address** (you can add **additional addresses** if you want)
4. Change status to **Enabled** and save the form
5. Now plugin is configured and activated

### Usage
Order's info page now have new card with title **QWQER Delivery**.

If you want to ship products via QWQER, you must click to this button in this card, and modal box will be shown for you.

The modal box have **3 sections**:
- **Pick up address (Your store's address):** You can chose other address if you have provide it in the configuration step.
- **Delivery address (Order shipping address):** Shipping destination, you able to change fields with your needs.
- **Delivery price:** Each QWQER order must be calculated first, so if you have changed some fields, or selected different store address, you must recalculate price of delivery, and only after that you can accept order delivery.

Also modal box has button **Accept delivery**, by clicking to it, QWQER delivery will be created and exchange will be included to the QWQER's invoice later.

After QWQER order created successfully do not forget to change store's order status to **Shipped** or something similar.

Store's order that are delivered by QWQER have new option to fetch current status, in the card with title **QWQER Delivery**,

So it you want to know current delivery status from QWQER, just click to green button **Get QWQER delivery status**.
