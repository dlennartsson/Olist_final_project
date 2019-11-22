# Olist_final_project

Our goal is to help Olist find out what sellers that shall be seen as not valuable

We will do this by implementing a review_score threshold for sellers. Below that threshold, sellers get removed from the platform.

Revenue As we have detailed previously, Olist charges sellers with various fees. For simplicity, we will assume that Olist takes 20% of the booking_value of sellers and charge 80 BRL by month per seller.

👉 Note: The booking_value is defined as the sum of product price. It excludes freight_value.

Cost

On the long term, bad customer experience has business implications: low repeat rate, immediate customer support cost, refund or non favorable word of mouth.

We will assume that we have an estimate measure of the monetary cost (in Brazilian Real) for each review
