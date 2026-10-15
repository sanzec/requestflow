RequestFlow — first-version requirements

Request form: 
The requester selects one fictional software tool and enters a justification. Both fields are required. 
The system identifies the requester from their login and records the submission time automatically.

Tool choices:
ReportStudio, CasePlanner, and AssetTrack.

Approval assignment:
For the first version, the system assigns requests to one designated approver account. 
Requesters cannot choose their approver or approve their own requests.

Submission: 
A valid submission creates a Pending request with a unique identifier and a submission history entry. 
An invalid submission displays an explanation and does not create a request.

Visibility:
Requesters can view only their own requests. The designated approver can view requests assigned to them.

Decisions:
Only Pending requests can be approved, rejected, or cancelled. Rejection requires a reason. Only the requester can cancel their request. 
Submitted requests cannot be edited. Approved, Rejected, and Cancelled requests remain visible in history and cannot change status again. 

Validation:
When the justification is empty or contains only whitespace, the system displays 'Enter a justification' and does not create a request.

