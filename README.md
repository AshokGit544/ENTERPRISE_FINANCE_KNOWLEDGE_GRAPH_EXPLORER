# Enterprise Finance Knowledge Graph Explorer

SAP FICO-style finance knowledge graph project using Python for entity relationship mapping, impact analysis, cluster detection, intelligent relationship search, and enterprise finance network analytics.

## Project Overview

This project shows how enterprise finance data can be connected like a network to understand relationships between:

- vendors
- cost centers
- profit centers
- GL accounts
- finance transactions

Instead of looking at only flat tables, this project builds a finance relationship model to show which entities are strongly connected and which entities have more business impact.

## Why this project is useful

In enterprise finance systems like SAP FICO, data is spread across many business entities.  
A normal report can show totals and trends, but this project helps answer deeper questions like:

- Which vendors are strongly linked to high-value cost centers?
- Which GL accounts are connected to important spending areas?
- Which entities are most influential in the finance network?
- Which clusters of finance activity are closely connected?
- How can we search relationship patterns using business language?

## What this project does

This project:

- generates SAP FICO-style finance master data
- generates synthetic finance transactions
- joins all entities into one analytical model
- builds relationship tables across finance entities
- creates a finance knowledge graph
- finds important and influential nodes
- performs impact analysis
- detects communities / clusters
- supports natural language relationship search

## Main entities used

- Vendors
- Cost Centers
- Profit Centers
- GL Accounts
- Finance Transactions

## Features

- Synthetic SAP FICO-style finance data
- Vendor to cost center relationships
- Vendor to GL account relationships
- Cost center to GL account relationships
- Vendor to profit center relationships
- Knowledge graph creation using NetworkX
- Centrality-based influence analysis
- Cluster / community detection
- Natural language relationship search
- Finance impact analysis

## Tech Stack

- Python
- pandas
- NumPy
- matplotlib
- networkx
- scikit-learn
- Jupyter Notebook / Google Colab

## Project flow

1. Create finance master data
2. Create finance transactions
3. Join all finance entities
4. Build relationship tables
5. Create finance knowledge graph
6. Calculate important nodes
7. Run impact analysis
8. Detect communities
9. Search relationships using natural language

## Output files

After running the notebook, files like these are generated:

- `vendors.csv`
- `cost_centers.csv`
- `profit_centers.csv`
- `gl_accounts.csv`
- `finance_transactions.csv`
- `vendor_cost_center_relationships.csv`
- `vendor_gl_relationships.csv`
- `cost_center_gl_relationships.csv`
- `vendor_profit_center_relationships.csv`
- `top_influential_nodes.csv`
- `relationship_documents.csv`
- `community_assignments.csv`
- `community_summary.csv`
- `top_vendor_cost_center_links.csv`
- `top_vendor_gl_links.csv`
- `top_cost_center_gl_links.csv`
- `node_summary.csv`

## Example business questions

This project can help answer questions like:

- vendors strongly connected to vegetation management
- entities related to emergency repairs and high value finance activity
- important cost centers connected to consulting and contractors
- profit centers connected to grid modernization and substation upgrades
- high impact vendor relationships in field operations

## Why this project is strong

This project is useful because it shows more than normal reporting.  
It shows how enterprise finance entities are connected and how business users can analyze those relationships in a smarter way.

It demonstrates:

- finance data modeling
- relationship analysis
- enterprise network thinking
- impact analysis
- search over connected business data
- graph-based business intelligence


## Skills demonstrated

- Python
- pandas
- NumPy
- finance data modeling
- graph analytics
- NetworkX
- impact analysis
- semantic-style search
- enterprise finance analytics

## How to run

1. Open the notebook in Google Colab
2. Install dependencies
3. Run all cells from top to bottom
4. Review the generated output files
5. Upload the notebook and outputs to GitHub
