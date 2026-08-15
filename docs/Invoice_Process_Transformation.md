# Process Transformation Example - Supplier Invoice Processing

## Current State

1. Supplier sends invoice by email or portal.
2. Accounts Payable employee opens the document.
3. Key fields are entered manually.
4. Employee searches for the related purchase order.
5. Quantity, price and supplier details are checked.
6. Exceptions are sent to the responsible buyer or approver.
7. Approved invoice is posted in the ERP system.
8. Employee archives supporting documentation.

### Main pain points

- Repetitive data entry
- Slow matching for simple invoices
- Manual hand-offs for exceptions
- Different handling depending on employee experience
- Limited visibility into where invoices are waiting

## Proposed Future State

1. Invoice enters the approved workflow.
2. Document AI extracts invoice fields.
3. System validates supplier and purchase-order information.
4. Matching rules check quantity, price and basic tolerances.
5. Clean matches are prepared automatically for approval/posting.
6. Exceptions are routed to a human with the reason highlighted.
7. Human approves financial exceptions.
8. Final transaction and audit information are stored in the ERP workflow.

## Why this is a good first pilot

The process is repetitive, has structured documents, has a clear business owner and can be measured using cycle time, touch time, exception rate and accuracy.

The future-state design intentionally keeps human approval for exceptions and financial controls.
