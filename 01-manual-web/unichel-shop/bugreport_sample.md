# Bug report example — Unichel Shop

**ID:** BR-WEB-002  
**Title:** Search with typo returns empty results due to backend typo handling  
**Severity:** Major  
**Priority:** High

## Environment
- Browser: Chrome (latest)
- OS: Windows 10/11

## Steps to reproduce
1. Open search
2. Enter query with 1 typo (example: `snikers` instead of `snickers`)
3. Submit

## Expected
Search returns suggestions or relevant results.

## Actual
Empty results. In Network response: backend returns response without typo correction.

## Attachments
- Screenshot/har log (sanitized)
