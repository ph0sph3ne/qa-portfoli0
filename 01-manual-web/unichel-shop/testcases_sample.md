# Sample test cases — Search & Filters

## TC-WEB-001 — Search exact match
**Preconditions:** app is available  
**Steps:**
1. Open search
2. Enter exact product name
3. Submit
**Expected:** relevant results are displayed, no errors

## TC-WEB-002 — Search with typo
**Steps:**
1. Enter query with 1 typo
2. Submit
**Expected:** either suggestions or relevant results; no 500 errors; response time acceptable

## TC-WEB-003 — Apply filter
**Steps:**
1. Apply price/size filter (example)
**Expected:** results update, filter chip visible, reset works
