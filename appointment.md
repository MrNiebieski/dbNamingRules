##appointment_rec##

`id`:

`userId`: link to user_info.id

`status`: ordered, paid, or serviced.

`apptTime`:

`paymentId`: link to payment_log.id

`timestamp`: automatically generated

---

###Relation to other tables###

`userId` = `user_info.id`


`paymentId` = `payment_log.id`