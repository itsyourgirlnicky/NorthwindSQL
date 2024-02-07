{
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/itsyourgirlnicky/NorthwindSQL/blob/main/index.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "id": "c706ed84",
      "metadata": {
        "deletable": false,
        "editable": false,
        "nbgrader": {
          "cell_type": "markdown",
          "checksum": "0e70a2387b5db31a026a0ff99f397aed",
          "grade": false,
          "grade_id": "cell-5ab1c1d5be55e778",
          "locked": true,
          "schema_version": 3,
          "solution": false,
          "task": false
        },
        "id": "c706ed84"
      },
      "source": [
        "# Structured Query Language (SQL) Checkpoint\n",
        "\n",
        "This checkpoint is designed to test your understanding of writing queries in the Structured Querying Language (SQL).\n",
        "\n",
        "Specifically, this checkpoint will cover:\n",
        "\n",
        "* Reading an Entity Relationship Diagram\n",
        "* Writing a query to return specific columns from a SQL database\n",
        "* Writing a query to filter the rows from a SQL database\n",
        "* Sorting observations using SQL\n",
        "* Joining tables using SQL\n",
        "\n",
        "## Data Understanding\n",
        "\n",
        "In this repository under the file path `Northwind.sqlite` there is a SQLite database file containing information about the fictional trading company \"Northwind Traders\".\n",
        "\n",
        "The tables of interest for this checkpoint will be:\n",
        "\n",
        "`Product`: A table containing information about products sold by Northwind Traders.\n",
        "\n",
        "`Order`: A table containing high level information about an order submitted to Northwind Traders.\n",
        "\n",
        "`Shipper`: A table containing information about the shipping companies Northwind Traders employ to handle the shipping of their products.\n",
        "\n",
        "\n",
        "## Requirements\n",
        "\n",
        "#### 1. Select an entire table.\n",
        "\n",
        "#### 2. Select all columns. Filter the rows.\n",
        "\n",
        "#### 3. Select a single column. Filter the rows using two conditions.\n",
        "\n",
        "#### 4. Sort in descending order. Return the first five rows.\n",
        "\n",
        "#### 5. Join two tables. Filter the rows.\n",
        "\n",
        "\n",
