# Schedule Change Request Process - Level 2 Decomposition

<style>
  .process-table {
    display: block;
    width: 100%;
    overflow-x: auto;
  }
  .process-table table {
    border-collapse: collapse;
    width: 100%;
  }
  .process-table th, .process-table td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
  }
  .process-table tr:nth-child(even) {
    background-color: #f2f2f2;
  }
  .process-table th {
    padding-top: 12px;
    padding-bottom: 12px;
    background-color: #f8f8f8;
  }
</style>

<div class="process-table">
<table>
  <thead>
    <tr>
      <th>L1 Step ID</th>
      <th>L1 Step Name</th>
      <th>Step Description (i.e., Level 2 Summary)</th>
      <th>L2 Step ID</th>
      <th>L2 Step Name/Short Description</th>
      <th>Dependent Steps (L1 or L2)</th>
      <th>Tools Used</th>
      <th>Code in TTS</th>
      <th>Step Owner (Group & Function)</th>
      <th>TTS Status</th>
      <th>Applicable Documentation</th>
      <th>Notification Required? (Group, Function & Verbatim)</th>
      <th>Approval Required?</th>
      <th>Approvers (Group & Function)</th>
      <th>Step Duration (days, hrs, min)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Agent Submits Change Request</td>
      <td>Agent submits a request to modify their schedule through the appropriate channels</td>
      <td>1.1</td>
      <td>Submit request via scheduling system</td>
      <td>None</td>
      <td>Scheduling Tool</td>
      <td>Yes</td>
      <td>Agent</td>
      <td>N/A</td>
      <td>Schedule Change Policy</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>1.2</td>
      <td>Provide required details (date, time, reason)</td>
      <td>1.1</td>
      <td>Scheduling Tool</td>
      <td>Yes</td>
      <td>Agent</td>
      <td>N/A</td>
      <td>Request Form Guidelines</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>1.3</td>
      <td>Submit supporting documentation if applicable</td>
      <td>1.2</td>
      <td>Email/Scheduling Tool</td>
      <td>Yes</td>
      <td>Agent</td>
      <td>N/A</td>
      <td>Documentation Policy</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Variable</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Validate Request</td>
      <td>Scheduling team reviews the request for completeness and adherence to policies</td>
      <td>2.1</td>
      <td>Review request details for completeness</td>
      <td>1.3</td>
      <td>Scheduling Tool</td>
      <td>Yes</td>
      <td>WFM Team</td>
      <td>Open</td>
      <td>Request Validation Checklist</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>2.2</td>
      <td>Verify agent eligibility (tenure, performance status)</td>
      <td>2.1</td>
      <td>HR System, Performance Dashboard</td>
      <td>Yes</td>
      <td>WFM Team</td>
      <td>In Progress</td>
      <td>Agent Eligibility Policy</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>2.3</td>
      <td>Check request against time-off policies</td>
      <td>2.2</td>
      <td>Scheduling Tool, Policy Database</td>
      <td>Yes</td>
      <td>WFM Team</td>
      <td>In Progress</td>
      <td>Time-Off Policy</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Coverage Adequate?</td>
      <td>Analyze staffing levels to determine if change request can be accommodated</td>
      <td>3.1</td>
      <td>Check forecasted call volume for requested timeframe</td>
      <td>2.3</td>
      <td>Forecasting Tool</td>
      <td>Yes</td>
      <td>WFM Analyst</td>
      <td>In Progress</td>
      <td>Forecasting Procedures</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>3.2</td>
      <td>Verify current staffing levels</td>
      <td>3.1</td>
      <td>Scheduling Tool</td>
      <td>Yes</td>
      <td>WFM Analyst</td>
      <td>In Progress</td>
      <td>Staffing Level Requirements</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>3.3</td>
      <td>Calculate impact on service level</td>
      <td>3.2</td>
      <td>WFM Analytics Tool</td>
      <td>Yes</td>
      <td>WFM Analyst</td>
      <td>In Progress</td>
      <td>Service Level Agreements</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Request Denied</td>
      <td>If coverage is inadequate, deny request and provide explanation</td>
      <td>4.1</td>
      <td>Document reason for denial</td>
      <td>3.3</td>
      <td>Scheduling Tool</td>
      <td>Yes</td>
      <td>WFM Team</td>
      <td>Pending</td>
      <td>Denial Documentation</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>4.2</td>
      <td>Suggest alternative options if available</td>
      <td>4.1</td>
      <td>Scheduling Tool</td>
      <td>Yes</td>
      <td>WFM Team</td>
      <td>Pending</td>
      <td>Alternative Options Guidelines</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td>5</td>
      <td>Update Schedule</td>
      <td>If coverage is adequate, process the schedule change</td>
      <td>5.1</td>
      <td>Apply schedule modification in system</td>
      <td>3.3</td>
      <td>Scheduling Tool</td>
      <td>Yes</td>
      <td>WFM Team</td>
      <td>Pending</td>
      <td>Schedule Modification Procedure</td>
      <td>No</td>
      <td>Yes</td>
      <td>Shift Supervisor</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>5.2</td>
      <td>Update related systems (payroll, attendance)</td>
      <td>5.1</td>
      <td>Scheduling Tool, HRIS, Payroll System</td>
      <td>Yes</td>
      <td>WFM Team</td>
      <td>Pending</td>
      <td>System Integration Procedures</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td>6</td>
      <td>Notify Agent</td>
      <td>Communicate the decision to the requesting agent</td>
      <td>6.1</td>
      <td>Generate automated notification</td>
      <td>4.2 or 5.2</td>
      <td>Notification System</td>
      <td>Yes</td>
      <td>System</td>
      <td>Complete</td>
      <td>Notification Templates</td>
      <td>Yes, Agent, Email</td>
      <td>No</td>
      <td>N/A</td>
      <td>Automated</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>6.2</td>
      <td>Document communication in agent record</td>
      <td>6.1</td>
      <td>CRM, Agent Record System</td>
      <td>Yes</td>
      <td>WFM Team</td>
      <td>Complete</td>
      <td>Record Keeping Standards</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Document Change</td>
      <td>Record the change details for reporting and auditing</td>
      <td>7.1</td>
      <td>Update change log</td>
      <td>6.2</td>
      <td>Change Management System</td>
      <td>Yes</td>
      <td>WFM Team</td>
      <td>Complete</td>
      <td>Change Log Procedures</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>7.2</td>
      <td>Document adherence to policy</td>
      <td>7.1</td>
      <td>Documentation System</td>
      <td>Yes</td>
      <td>WFM Team</td>
      <td>Complete</td>
      <td>Policy Compliance Records</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Minutes</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Update Reports</td>
      <td>Ensure all reporting reflects the approved changes</td>
      <td>8.1</td>
      <td>Update staffing reports</td>
      <td>7.2</td>
      <td>Reporting System</td>
      <td>Yes</td>
      <td>WFM Analyst</td>
      <td>Complete</td>
      <td>Staffing Report Procedures</td>
      <td>Yes, Management Team, Email</td>
      <td>No</td>
      <td>N/A</td>
      <td>Hours</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>8.2</td>
      <td>Reconcile change tracking for monthly analysis</td>
      <td>8.1</td>
      <td>Analytics System</td>
      <td>Yes</td>
      <td>WFM Analyst</td>
      <td>Complete</td>
      <td>Monthly Reconciliation Process</td>
      <td>No</td>
      <td>No</td>
      <td>N/A</td>
      <td>Hours</td>
    </tr>
  </tbody>
</table>
</div>