Deadline: 17th Jan
Soft Deadline: 14th Jan

Task 1: Retrieving and Preparing the Data
- The  goal of the project: order cancellation
- Pre-process data: data cleaning
    - Missing values
    - Correct data type
- Create "OrderCancelled" column from "InvoiceNo"

(Trung)
- InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
- OrderCancelled

(Thao)
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invice date and time. Numeric. The day and time when a transaction was generated.

(Hoang)
- UnitPrice: Unit price. Numeric. Product price per unit in sterling (Â£).
- CustomerID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal. The name of the country where a customer resides.


(Trung) select based on ALL data

Task 2: Feature Engineering 
- Select relevant columns: use corr() => select all columns with high correlation
Note: These steps must be performed consistently for train/val/test sets.

Task 3: Data Modelling
- Model the data by treating it as Clustering AND Classification Task

Qs:
- "These steps must be performed consistently for train/val/test sets" => when do split data?
- "You must use at least two different models for each approach" => confirm select 2 approaches?

Task 4: Report:

Create PDF: https://docs.google.com/document/d/1Xp_-m0HaH1vw3eBdGQDE0IwwjcMSG8yXpYFJeAdOhV8/edit

Task 5: Presentation

prepare 10-12 slides for in-class presentation anddemonstration.


Phase 1: Task 1 + Task 2 (for all data set) (Deadline: 5th Jan)

Phase 2: Data modelling (5th -> 12th Jan)

Phase 3: Report + Presentation slides (12th -> 14th Jan)