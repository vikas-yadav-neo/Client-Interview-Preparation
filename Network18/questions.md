# Network18 Interview Questions

## Interview 1

1. **Explain about the DE projects that you've worked on.**
2. **PySpark Coding Questions:**
   - Suppose you have a DataFrame with columns `timestamp`, `events`, and `user_id`:
     1. Fetch the time spent by the user based on the events.
     2. Count the events performed by the user day-wise.
3. **Explain what window functions are, with examples.**
4. **Explain the difference between `RANK` and `DENSE_RANK`.**

---

## Interview 2

1. **Explain any pipeline you have created in your project.**
2. **Explain Linked Service.**
3. **What is IR and its types?**
4. **Scenario-based Questions:**
   - Suppose you have 4 on-premises machines, each containing different sets of data that you want to move into the cloud using Azure Data Factory. In this case, how many Linked Services, Datasets, and Integration Runtimes (IRs) would you need?
   - How do you handle incremental loads in ADF?
5. **Suppose you have 2 tables:**
   - `department` (less than 10MB): `dep_id`, `dep_name`
   - `employee` (10GB): `emp_id`, `name`, `salary`, `gender`, `DOJ`, `dep_id`
   - Write optimized code to join the DataFrames.
   - Given a column `gender` with values "Male" and "Female", replace:
     - "Female" → "Male"
     - "Male" → "Female"