# Security Governance Semantic Model Test Prompts

## **EASY-MEDIUM PROMPTS** 
*Testing basic functionality and verified queries*

### **Login Security Monitoring**
1. "Show me failed login attempts"
2. "What are the failed logins in the last 7 days?"
3. "Show me users with login failures"
4. "Which IP addresses have failed login attempts?"
5. "Show me successful logins today"

### **User Authentication Analysis**
6. "Who are the top users by login count?"
7. "Show me users who logged in yesterday"
8. "Which users use MFA?"
9. "Show me password authentication vs key pair usage"
10. "Which authentication methods are being used?"

### **Session Management**
11. "Show me active sessions"
12. "What are current sessions by authentication method?"
13. "Show me sessions created today"
14. "Which users have the longest sessions?"
15. "Show me recently closed sessions"

### **User Account Status**
16. "Show me disabled users"
17. "Which users must change their password?"
18. "Show me user account statuses"
19. "When was each user created?"
20. "Show me users by default role"

### **Basic Access Rights**
21. "What permissions does ANALYST_USER have?"
22. "Show me user privileges"
23. "Which users have SELECT access?"
24. "Show me role assignments"
25. "What roles are granted to users?"

## **HARD PROMPTS**
*Testing cross-table relationships and business logic*

### **Security Incident Analysis**
26. "Show me suspicious login activity with multiple IP addresses"
27. "Find users with unusual authentication patterns"
28. "Which users have high failure rates?"
29. "Show me geographic anomalies in login patterns"
30. "Find users logging in outside business hours"

### **Multi-Factor Authentication Compliance**
31. "Which users are not using MFA?"
32. "Show me MFA adoption rates by user"
33. "Compare authentication methods across users"
34. "Which users rely only on passwords?"
35. "Show me users who should enable MFA"

### **Privilege Escalation Detection**
36. "Show me users with excessive privileges"
37. "Which users have admin-level access?"
38. "Find users with both direct and role-based grants"
39. "Show me privilege changes over time"
40. "Which users can grant privileges to others?"

### **Session Security Analysis**
41. "Find users with multiple concurrent sessions"
42. "Show me session duration patterns by user"
43. "Which users have abandoned sessions?"
44. "Find sessions from suspicious IP addresses"
45. "Show me client application usage patterns"

### **Data Governance & Policy Compliance**
46. "Which objects are protected by masking policies?"
47. "Show me row access policy implementations"
48. "Which users can access policy-protected data?"
49. "Find objects without proper data protection"
50. "Show me policy compliance by object type"

### **Cross-Domain Security Analysis**
51. "Correlate failed logins with successful sessions"
52. "Show me users who bypass normal authentication"
53. "Find users with database access but no recent logins"
54. "Which roles have conflicting privilege assignments?"
55. "Show me users with access but no active sessions"

### **Advanced Threat Detection**
56. "Find potential brute force attack patterns"
57. "Show me users with rapid successive login attempts"
58. "Which IP addresses show scanning behavior?"
59. "Find users with authentication method changes"
60. "Show me dormant accounts with recent activity"

### **Compliance Reporting**
61. "Generate user access audit report"
62. "Show me privileged user activity summary"
63. "Which users have administrative database access?"
64. "Find users violating least privilege principle"
65. "Show me access rights by sensitivity level"

### **Geographic Security Analysis**
66. "Which users login from multiple countries?"
67. "Show me login patterns by geographic region"
68. "Find users with VPN vs direct connections"
69. "Which IP ranges are most commonly used?"
70. "Show me international login activity"

### **Client Security Assessment**
71. "Which client applications are most vulnerable?"
72. "Show me outdated client versions in use"
73. "Find users with unsupported client software"
74. "Which JDBC/ODBC versions need updating?"
75. "Show me client security compliance"

### **Time-Based Security Patterns**
76. "Show me login patterns during off-hours"
77. "Which users work unusual schedules?"
78. "Find weekend vs weekday security patterns"
79. "Show me holiday period access anomalies"
80. "When do most security incidents occur?"

### **Identity Lifecycle Management**
81. "Show me recently created vs recently accessed users"
82. "Find dormant user accounts"
83. "Which users haven't logged in recently?"
84. "Show me user lifecycle compliance"
85. "Find users who should be deprovisioned"

### **Advanced Authentication Analysis**
86. "Compare OAuth vs traditional authentication security"
87. "Show me SSO adoption and effectiveness"
88. "Which users have the most authentication failures?"
89. "Find users with authentication bypass attempts"
90. "Show me two-factor authentication effectiveness"

### **Data Access Security Correlation**
91. "Correlate user privileges with actual data access"
92. "Show me users with unused privileges"
93. "Find privilege creep in user accounts"
94. "Which users exceed their role requirements?"
95. "Show me access rights vs usage patterns"

### **Emergency Response Scenarios**
96. "Find all active sessions for a compromised user"
97. "Show me recent access by terminated employees"
98. "Which users can access sensitive financial data?"
99. "Find all admin-level activities in last 24 hours"
100. "Show me emergency access usage patterns"
