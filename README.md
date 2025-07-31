# Interactive User Table

This project is an interactive user table that allows filtering and sorting data. It demonstrates skills in working with React, managing state, optimizing rendering, and using URL Search Params to preserve application state.

## Preview link

- [DEMO LINK](https://nbryk.github.io/interactive-user-table/)

---

### **Technologies**

- **React:**
- **TypeScript:**
- **SCSS:**
- **Git:**
- **GitHub Pages:**

---

### **Features**

- **Filtering:**

  - **Name Search:** The `NameFilter` allows you to search for people by their `name`, `motherName`, or `fatherName` (case-insensitive). The `query` search parameter in the URL updates in real-time.
  - **Century Filter:** The `CenturyFilter` enables the selection of one or multiple centuries. Selected values are added to the URL as `centuries` search parameters.
  - Filters are displayed only after the data has finished loading.

- **Sorting:**

  - Data can be sorted by **Name**, **Sex**, **Born**, and **Died** by clicking on the arrows in the table headers.
  - Sorting has three states: ascending, descending, and disabled.
  - The sort state is reflected in the URL using the `sort` and `order` search parameters.

- **URL Synchronization:**
  - All filtering and sorting parameters are stored in the URL (as search params), making it easy to share a specific view of the table.
  - The table's state is preserved when navigating within the People page.

---

### **Run locally**

1.  Clone the repository: git clone [link on repository]
2.  Open with VSCode: code interactive-user-table
3.  Go to branch develop: git checkout develop
4.  Install the dependencies: npm install
5.  Run the project: npm start
6.  Open the address that the local server displays in your browser.
