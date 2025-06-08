## 🧠 Basic Workflow in LangGraph

LangGraph operates using a graph-based structure where tasks are broken down into logical components. The basic workflow includes the following key elements:

### 🔹 Nodes

* Represent the core logic or **individual tasks** to be executed.
* Each node performs a specific function in the pipeline (e.g., querying a model, filtering input, etc.).

### 🔹 Edges

* **Connect the nodes**, establishing the flow of data and execution.
* Control the direction and logic of the graph’s traversal.

### 🔹 State

* Acts as the **data structure** passed between nodes.
* It contains all inputs and outputs and evolves over time as it moves through the graph.
* Defined using a **state schema** (like a Pydantic model).

### 🔹 StateGraph

* Represents the **entire structure** of the graph.
* Combines all nodes, edges, and state transitions into a cohesive workflow.

---
