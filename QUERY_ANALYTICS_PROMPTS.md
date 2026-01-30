# Query Analytics Semantic Model Test Prompts

## **EASY-MEDIUM PROMPTS** 
*Testing basic functionality and verified queries*

### **Basic Query Performance**
1. "Show me the slowest queries"
2. "What are the top 10 longest running queries?"
3. "Show me queries that took more than 30 seconds"
4. "Which queries failed yesterday?"
5. "Show me queries with errors"

### **User Activity**
6. "Who are the heaviest users?"
7. "Show me queries by BSMITH"
8. "Which users ran the most queries?"
9. "Show me all users who ran queries today"
10. "Who ran queries on ANALYTICS_WH warehouse?"

### **Warehouse Usage**
11. "Show me queries by warehouse"
12. "Which warehouse had the most queries?"
13. "Show me COMPUTE_WH usage"
14. "What warehouses are being used?"
15. "Show me warehouse query counts"

### **Credit Consumption**
16. "Show me expensive queries"
17. "Which queries consumed the most credits?"
18. "Show me credit usage by warehouse"
19. "What are the top 5 credit consuming queries?"
20. "Show me queries that used more than 1 credit"

### **Object Access**
21. "Show me object names accessed in recent queries"
22. "What tables were accessed yesterday?"
23. "Show me recent object access"
24. "Which objects are being queried?"
25. "Show me database access patterns"

## **HARD PROMPTS**
*Testing cross-table relationships and business logic*

### **Performance Analysis**
26. "Show me warehouse performance metrics"
27. "Compare query performance across warehouses"
28. "Show me cache hit rates by user"
29. "Which queries have poor cache performance?"
30. "Show me compilation time vs execution time"

### **Cost Analysis**
31. "Show me cost per GB scanned"
32. "Which users generate the highest costs?"
33. "Show me warehouse cost efficiency"
34. "Compare credit usage between small and large warehouses"
35. "Show me queries with high cost but low row output"

### **Time-based Analysis**
36. "Show me query patterns over the last week"
37. "Compare this week vs last week query performance"
38. "Show me peak usage hours"
39. "When do we have the most expensive queries?"
40. "Show me weekend vs weekday usage patterns"

### **Error Analysis**
41. "What are the most common error codes?"
42. "Show me users with the highest failure rates"
43. "Which warehouses have the most failed queries?"
44. "Show me syntax errors vs runtime errors"
45. "What queries fail most frequently?"

### **Object Access (Intermediate)**
46. "Show me policy-protected data access"
47. "Which users access sensitive data?"
48. "Show me DDL operations performed"
49. "What objects were modified recently?"
50. "Show me view vs table access patterns"

### **Queue Analysis**
51. "Show me queries that waited for provisioning"
52. "Which warehouses have queuing issues?"
53. "Show me overload vs provisioning wait times"
54. "What causes our longest queue times?"
55. "Show me blocked vs queued queries"