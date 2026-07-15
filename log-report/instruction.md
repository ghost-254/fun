Read the Apache-style access log at /app/access.log and write a traffic summary to /app/report.json. Each nonempty line represents one request. The client IP is the first whitespace-delimited field, and the requested path is the second token inside the quoted HTTP request field.

Success criteria:

1. /app/report.json must be valid UTF-8 JSON containing one object with exactly the keys "total_requests", "unique_ips", and "top_path". No additional keys are permitted.
2. "total_requests" must be a JSON integer equal to the number of nonempty log lines, and "unique_ips" must be a JSON integer equal to the number of distinct client IP addresses.
3. "top_path" must be a JSON string equal to the requested path that appears most frequently in the log.

You have 120 seconds to complete this task. Do not cheat by using online solutions or hints specific to this task.
