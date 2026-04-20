# API Testing – Sample (Postman)

## Tool Used
Postman

## Endpoint Tested
GET https://jsonplaceholder.typicode.com/posts

## Request Details
- Method: GET
- URL: https://jsonplaceholder.typicode.com/posts

## Test Case 1: Verify status code
**Steps:**
1. Open Postman
2. Select GET method
3. Enter the endpoint URL
4. Click Send

**Expected Result:**
Status code should be 200 OK

**Actual Result:**
Status code returned: 200 OK

---

## Test Case 2: Verify response body structure
**Steps:**
1. Send GET request
2. Inspect the response body

**Expected Result:**
Response should return a JSON array of posts containing:
- userId
- id
- title
- body

**Actual Result:**
Response returned a JSON array of posts with the expected fields:
- userId
- id
- title
- body

---

## Test Case 3: Verify response time
**Steps:**
1. Send GET request
2. Check the response time shown in Postman

**Expected Result:**
Response time should be under 2 seconds

**Actual Result:**
Response time was 288 ms

---

## Summary
The API request was executed successfully in Postman.
- Status: 200 OK
- Response Time: 288 ms
- Response Type: JSON array
- Result: Passed
