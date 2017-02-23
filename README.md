# Widgets Description

## Table of Contents

|[GC Widgets](#gc-widgets)|[SUB Widgets](#sub-widgets) |
| :-------------: |:-------------:|
|[Active Projects](#active-projects)|[General Details](#general-details)|
|[Average Q Score](#average-q-score)|[Q Score Breakdown](#q-score-breakdown)|
|[Subs With Liens](#subs-with-liens)|[Key Ratios](#key-ratios)|
|[Total Project Valuation](#total-project-valuation)|[Active Contracts](#active-contracts)|
|[Total Active Contracts](#total-active-contracts)|[Lumbermens Credit Report](#lumbermens-credit-report)|
|[Subs With Stale Data](#subs-with-stale-data)|[Executive Focus](#executive-focus)|
|[Subs Scored](#subs-scored)|[Company Structure](#company-structure)|
|[Data Completeness](#data-completeness)|  |
|[Q Score By Trades](#q-score-by-trades)|  |
|[Valuation By Trade](#valuation-by-trade)|  |
|[Provincial Exposure by QScore](#provincial-exposure-by-qscore)|  |
|[Provincial Exposure by Dollar](#provincial-exposure-by-dollar)|  |
|[Top 10 Subcontractors <br/>by Number of Contract](#top-10-subcontractors-by-number-of-contract)|  |
|[Top 10 Subcontractors With<br/> Largest Dollar Contract](#top-10-subcontractors-with-largest-dollar-contract)|  |
|[Top 10 Subcontractors <br/> by Exposure to GC](#top-10-subcontractors-by-exposure-to-gc)| |

## GC Widgets

+ #### Active Projects
  the total number of active projects

  ```json
  {
    "data": [
      {
        "value": 500
      }
    ],
    "display_name": "Active Projects",
    "id": "0193345a2f4077220bb11934",
    "name": "active_projects",
    "type": "gc"
  }

  ```

+ #### Average Q Score
  the average q-score of all active subs associated with the gc

  ```json
  {
    "data": [
      {
        "value": 4.2
      }
    ],
    "display_name": "Average Q Score",
    "id": "00ab1cdfaf40772209918abc",
    "name": "average_score",
    "type": "gc"
  }

  ```

+ #### Subs With Liens
  the percentage of subs with liens

  ```json
  {
    "data": [
      {
        "total": 1756,
        "value": 14.8
      }
    ],
    "display_name": "Subs With Liens",
    "id": "abcd332213455632209918ab",
    "name": "percent_subs_liens",
    "type": "gc"
  }

  ```

+ #### Active GC Subs
  the total number of active subs associated with the gc

  ```json
  {
    "data": [
      {
        "value": 1752
      }
    ],
    "display_name": "Active GC Subs",
    "id": "abcdf3341234998454abbdff",
    "name": "total_active_subs",
    "type": "gc"
  }

  ```

+ #### Total Project Valuation
  the total dollar amount of all active contracts

  ```json
  {
    "data": [
      {
        "value": 16403747860.72
      }
    ],
    "display_name": "Total Project Valuation",
    "id": "112334541234998454abbdff",
    "name": "total_project_valuation",
    "type": "gc"
  }

  ```

+ #### Total Active Contracts
  the total number of active contracts

  ```json
  {
    "data": [
      {
        "value": 12360
      }
    ],
    "display_name": "Total Active Contracts",
    "id": "1194abbdfe34998454abbdff",
    "name": "total_active_contracts",
    "type": "gc"
  }

  ```

+ #### Subs With Stale Data
  1. the total number of subs with stale data
  2. the percentage of subs with stale data <br/>

  ```json
  {
    "data": [
      {
        "total": 456,
        "value": 78.49
      }
    ],
    "display_name": "Subs With Stale Data",
    "id": "1111abbdfe34998454abbdff",
    "name": "subs_stale_data",
    "type": "gc"
  }

  ```

+ #### Subs Scored
  1. the total number of subs that have q-score
  2. the percentage of subs that have q-score <br/>

  ```json
  {
    "data": [
      {
        "total": 581,
        "value": 36.38
      }
    ],
    "display_name": "Subs Scored",
    "id": "1112abbdfe34998454abbdff",
    "name": "percent_subs_scored",
    "type": "gc"
  }

  ```

+ #### Data Completeness
  the average percentage of data completeness for all subs

  ```json
  {
    "data": [
      {
        "total": 581,
        "value": 85.03
      }
    ],
    "display_name": "Data Completeness",
    "id": "1119245a2f4077220bb11934",
    "name": "gc_data_completeness",
    "type": "gc"
  }

  ```

+ #### Q Score By Trades
  the percentage of each q-score for each trade

  ```json
  {
    "data": [
      {
        "id": "aa769037-8828-4af2-9165-5d0fab2f93af",
        "trade": "EXISTING CONDITIONS",
        "trade_abbrev": "EXCD",
        "value": {
          "N/A": 0,
          "Q1": 0,
          "Q2": 11.11,
          "Q3": 14.81,
          "Q4": 37.04,
          "Q5": 33.33,
          "Q6": 3.7,
          "Q7": 0
        }
      },
      {
        "id": "0d5040bf-820e-447c-8a10-8402c4e15d99",
        "trade": "PLUMBING",
        "trade_abbrev": "PLMB",
        "value": {
          "N/A": 0,
          "Q1": 0,
          "Q2": 0,
          "Q3": 25,
          "Q4": 50,
          "Q5": 25,
          "Q6": 0,
          "Q7": 0
        }
      }
    ],
    "display_name": "Q Score by Trades",
    "id": "111339918f40772209918abc",
    "name": "score_trades",
    "type": "gc"
  }
  ```

+ #### Valuation By Trade
  total dollar amount of each trade

  ```json
  {
    "data": [
      {
        "trade": "EXISTING CONDITIONS",
        "trade_id": "aa769037-8828-4af2-9165-5d0fab2f93af",
        "value": 100127283.07
      },
      {
        "trade": "PLUMBING",
        "trade_id": "0d5040bf-820e-447c-8a10-8402c4e15d99",
        "value": 128954696.23
      },
      {
        "trade": "ELECTRICAL",
        "trade_id": "0c42bc4f-83c9-49d7-8cc9-cc41c842bb40",
        "value": 615652812.09
      },
      {
        "trade": "FINISHES",
        "trade_id": "c6ce32cb-5349-4d49-bb7a-746135dcfbc6",
        "value": 781382608.82
      },
      {
        "trade": "WOOD, PLASTICS AND COMPOSITES",
        "trade_id": "ad58dba7-58ae-4925-9b7c-f42f5859764c",
        "value": 164781454.92
      }
    ],
    "display_name": "Valuation By Trade",
    "id": "111439918f40772209918abc",
    "name": "valuation_by_trade",
    "type": "gc"
  }
  ```

+ #### Provincial Exposure by QScore
  the average q-score of each province

  ```json
  {
    "data": [
      {
        "province": "BC",
        "q_score": 4.5,
        "total_subs": 93
      },
      {
        "province": "ON",
        "q_score": 4.5,
        "total_subs": 286
      },
      {
        "province": "NL",
        "q_score": 4.8,
        "total_subs": 11
      },
      {
        "province": "NS",
        "q_score": 4.7,
        "total_subs": 14
      },
      {
        "province": "SK",
        "q_score": 4.6,
        "total_subs": 55
      }
    ],
    "display_name": "Provincial Exposure by QScore",
    "id": "111639918f40772209918abc",
    "name": "province_exposure_score",
    "type": "gc"
  }

  ```

+ #### Provincial Exposure by Dollar
  1. total contract dollar amount for each province
  2. the percentage of dollar amount relative to total contract value <br/>
     for each province <br/>

  ```json
  {
    "data": [
      {
        "province": "BC",
        "total": 1335280621.39,
        "value": 8.14
      },
      {
        "province": "ON",
        "total": 9749509740.02,
        "value": 59.43
      },
      {
        "province": "NL",
        "total": 163996741.59,
        "value": 1.0
      },
      {
        "province": "NS",
        "total": 118387645.92,
        "value": 0.72
      },
      {
        "province": "SK",
        "total": 432949099.89,
        "value": 2.64
      }
    ],
    "display_name": "Provincial Exposure by Dollar",
    "id": "111739918f40772209918abc",
    "name": "province_exposure_dollar",
    "type": "gc"
  }

  ```

+ #### Top 10 Subcontractors by Number of Contract
  the top 10 subs ranked by total number of contracts with the gc

  ```json
  {
    "data": [
      {
        "active_contracts": 1000,
        "contracts_with_gc": 102,
        "legal_entity_id": "0b3012bb-f919-4399-b69e-048328fd2f72",
        "name": "Trotter & Morton Building Technologies Inc.",
        "q_score": null,
        "trade": null,
        "trade_rank": null,
        "value": 746505906.9
      },
      {
        "active_contracts": 200,
        "contracts_with_gc": 64,
        "legal_entity_id": "4ee58807-f301-41e6-81ef-a91d0573f4ee",
        "name": "Upper Canada Specialty Hardware Limited",
        "q_score": 5.0,
        "trade": "OPENINGS",
        "trade_rank": 27.0,
        "value": 86096940.3
      },
      {
        "active_contracts": 44,
        "contracts_with_gc": 55,
        "legal_entity_id": "50284d22-4dd1-4e5d-af2d-627d4c3987ee",
        "name": "North Wood Carpet & Tile Company Ltd.",
        "q_score": null,
        "trade": null,
        "trade_rank": null,
        "value": 58250881.41
      }
    ],
    "display_name": "Top 10 Subcontractors by Number of Contract",
    "id": "1343425a2f4077220bb11934",
    "name": "top_subs_largest_number_of_contract",
    "type": "gc"
  }
  ```

+ #### Top 10 Subcontractors With Largest Dollar Contract
  the top 10 contracts ranked by current dollar amount

  ```json
  {
    "data": [
      {
        "contract_id": "4e9e8e5e-958e-4a97-b94d-f17940162ed2",
        "legal_entity_id": null,
        "name": null,
        "project_id": "a221d000-ed32-4d2f-8540-ebd4897332b4",
        "project_name": "SOUTH HEALTH CAMPUS SUBTRADES",
        "q_score": null,
        "trade": null,
        "trade_rank": null,
        "value": 242085758.08
      },
      {
        "contract_id": "447b647d-fd9e-4938-b9db-cc84f44e7c5c",
        "legal_entity_id": "3552f7a5-7309-4e12-80ec-6834ca2150ac",
        "name": "Geo. A. Kelson Company Limited",
        "project_id": "edaa7606-1547-4e58-abf5-ba5fc35089b4",
        "project_name": "NEW OAKVILLE HOSPITAL",
        "q_score": null,
        "trade": null,
        "trade_rank": null,
        "value": 207079403.23
      },
      {
        "contract_id": "6425aba5-8c75-4bd4-8b83-231203e2ccd5",
        "legal_entity_id": "0b3012bb-f919-4399-b69e-048328fd2f72",
        "name": "Trotter & Morton Building Technologies Inc.",
        "project_id": "a221d000-ed32-4d2f-8540-ebd4897332b4",
        "project_name": "SOUTH HEALTH CAMPUS SUBTRADES",
        "q_score": null,
        "trade": null,
        "trade_rank": null,
        "value": 205534169.75
      }
    ],
    "display_name": "Top 10 Subcontractors With Largest Dollar Contract",
    "id": "1120245a2f4077220bb11934",
    "name": "top_subs_largest_dollar_contract",
    "type": "gc"
  }
  ```

+ #### Top 10 Subcontractors by Exposure to GC
  the top 10 subs ranked by contracts dollar exposure value to the gc

  ```json
  {
    "data": [
      {
        "active_contracts": 1000,
        "contracts_with_gc": 102,
        "exposure_percent": 6.76,
        "legal_entity_id": "0b3012bb-f919-4399-b69e-048328fd2f72",
        "name": "Trotter & Morton Building Technologies Inc.",
        "q_score": null,
        "trade": null,
        "trade_rank": null,
        "value": 746505906.9
      },
      {
        "active_contracts": 20,
        "contracts_with_gc": 30,
        "exposure_percent": 4.19,
        "legal_entity_id": "3552f7a5-7309-4e12-80ec-6834ca2150ac",
        "name": "Geo. A. Kelson Company Limited",
        "q_score": null,
        "trade": null,
        "trade_rank": null,
        "value": 463175398.03
      },
      {
        "active_contracts": 1,
        "contracts_with_gc": 5,
        "exposure_percent": 3.31,
        "legal_entity_id": "ab57441c-5354-49ca-84c6-29b5a9a079aa",
        "name": "Univex (Ontario) Limited",
        "q_score": null,
        "trade": null,
        "trade_rank": null,
        "value": 365853933.26
      }
    ],
    "display_name": "Top 10 Subcontractors by Exposure to GC",
    "id": "1121245a2f4077220bb11934",
    "name": "top_subs_current_contract",
    "type": "gc"
  }

  ```

## SUB Widgets

+ #### General Details
  the general information

  ```json
  {
    "data": [
      {
        "csid": "CA362255700LL7",
        "description": null,
        "email": null,
        "location": {
          "address": "6772 14th Avenue",
          "city": "MARKHAM",
          "country": "CA",
          "fax": "9052942761",
          "phone": "9052947090",
          "postal-zip": "L6B 1A8",
          "province-state": "ON"
        },
        "name": "Greenfield Painting Services D/O Glover and Associates Painting Limited",
        "trades": [
          {
            "name": "FINISHES",
            "type": "primary"
          }
        ],
        "url": ""
      }
    ],
    "display_name": "General Details",
    "id": "1111145a2f4077220bb11934",
    "name": "general_details",
    "type": "sub"
  }

  ```

+ #### Q Score Breakdown
  the q-score and delta

  ```json
  {
    "data": [
      {
        "delta": null,
        "q_score": 3.2
      }
    ],
    "display_name": "Q Score Breakdown",
    "id": "1111245a2f4077220bb11934",
    "name": "score_breakdown",
    "type": "sub"
  }

  ```

+ #### Key Ratios
  six key financial ratios:
  - quick ratio (percentage)
  - workinkg capital turnover (decimal)
  - net profit ratio (percentage)
  - debt to equity (decimal)
  - backlog to working capital (decimal)
  - working capital adequacy (decimal) <br/>

  ```json
  {
    "data": [
      {
        "name": "Quick Ratio",
        "ratio": 3.81,
        "trade_average": 3.21
      },
      {
        "name": "Working Capital Turnover",
        "ratio": 1.92,
        "trade_average": 8.39
      },
      {
        "name": "Net Profit Ratio",
        "ratio": 0.08,
        "trade_average": 0.13
      },
      {
        "name": "Debt To Equity",
        "ratio": 0.01,
        "trade_average": 2.07
      },
      {
        "name": "Backlog To Working Capital",
        "ratio": 0.24,
        "trade_average": 1.8
      },
      {
        "name": "Working Capital Adequacy",
        "ratio": 0.23,
        "trade_average": 0.3
      }
    ],
    "display_name": "Key Ratios",
    "id": "1111945a2f4077220bb11934",
    "name": "key_ratios",
    "type": "sub"
  }

  ```

+ #### Similar Subs
  get the list of 5 higher ranked and 5 lower ranked subs with the same trade <br/>

  ```json
  {
    "data": [
      {
        "contracts": {
          "average": 146011.11,
          "total": 10512800
        },
        "display_name": "Flesher Marble & Tile 1910 Ltd.",
        "legal_entity_id": "e79d08ae-ab37-40ff-b782-de83f6d29a31",
        "liens": {
          "outstanding": 358161,
          "total": 2
        },
        "q_score": 3.2,
        "trade_rank": 14
      },
      {
        "contracts": {
          "average": 28571.43,
          "total": 6000000
        },
        "display_name": "Greenfield Painting Services D/O Glover and Associates Painting Limited",
        "legal_entity_id": "d0277f06-caec-4f0f-8279-71fa2220f789",
        "liens": {
          "outstanding": null,
          "total": null
        },
        "q_score": 3.2,
        "trade_rank": 15
      },
      {
        "contracts": {
          "average": 74074.07,
          "total": 2000000
        },
        "display_name": "Inter-Provincial Painting Limited",
        "legal_entity_id": "ce4bdba2-0a9b-4912-be35-18e71fb71edf",
        "liens": {
          "outstanding": null,
          "total": null
        },
        "q_score": 3.3,
        "trade_rank": 16
      }
    ],
    "display_name": "Similar Subs",
    "id": "1111645a2f4077220bb11934",
    "name": "similar_subs",
    "type": "sub"
  }
  ```

+ #### Active Contracts
  the list of all active contracts

  ```json
  {
    "data": [
      {
        "created": 1487363183,
        "current_contract_value": 3303924.85,
        "gc_id": "c90e05bb-92b7-4c5f-b31e-bb0adf1d9771",
        "gc_name": "Ellis Don",
        "id": "cdb20e07-9cba-486f-b665-5abce9da8251",
        "project_id": "edaa7606-1547-4e58-abf5-ba5fc35089b4",
        "project_name": "NEW OAKVILLE HOSPITAL",
        "trade_id": "c6ce32cb-5349-4d49-bb7a-746135dcfbc6",
        "trade_name": "FINISHES",
        "updated": 1487363183
      },
      {
        "created": 1487363183,
        "current_contract_value": 2570303.12,
        "gc_id": "c90e05bb-92b7-4c5f-b31e-bb0adf1d9771",
        "gc_name": "Ellis Don",
        "id": "27e66715-f5c3-403d-9d51-740cbd7bc80d",
        "project_id": "297e67db-2c23-4343-8501-ce6a5f784417",
        "project_name": "PAN AM ATHLETES VILLAGE JV",
        "trade_id": "c6ce32cb-5349-4d49-bb7a-746135dcfbc6",
        "trade_name": "FINISHES",
        "updated": 1487363183
      }
    ],
    "display_name": "Active Contracts",
    "id": "1111745a2f4077220bb11934",
    "name": "active_contracts",
    "type": "sub"
  }
  ```

+ #### Data Completeness
  the percentage of data completeness for business data, financial data,<br/>
  health safety data and total data

  ```json
  {
    "data": [
      {
        "id": "business_data",
        "name": "% Business Factors Submitted",
        "value": 100.0
      },
      {
        "id": "financial_data",
        "name": "% Financial Metrics Submitted",
        "value": 100.0
      },
      {
        "id": "health_safety_data",
        "name": "% Health and Safety Submitted",
        "value": null
      },
      {
        "id": "total",
        "name": "% of Overall Data Completeness",
        "value": 100.0
      },
      {
        "id": "trade_average",
        "name": "Trade Average",
        "value": 83.71
      }
    ],
    "display_name": "Data Completeness",
    "id": "1111845a2f4077220bb11934",
    "name": "sub_data_completeness",
    "type": "sub"
  }
  ```

+ #### Lumbermens Credit Report
  the lien information

  ```json
  {
    "data": [
      {
        "date_last_lien": 1425229200,
        "info": {
          "logo": "http://compass-logos.s3-website-us-east-1.amazonaws.com/lumbermen/logo.jpg",
          "url": "http://www.lumbermen.com"
        },
        "last_five_years": 1.0,
        "total_last_five_years": 1002.0,
        "total_last_lien": 1002
      }
    ],
    "display_name": "Lumbermens Credit Report",
    "id": "1112045a2f4077220bb11934",
    "name": "lumbermens_credit_report",
    "type": "sub"
  }

  ```

+ #### Executive Focus
  the information of executive employees

  ```json
  {
    "data": [
      {
        "name": "Dan Stewart",
        "position": "Owner/President",
        "time_in_position": 15.0,
        "time_with_firm": 15.0
      },
      {
        "name": "Kelly Stewart",
        "position": "Office Manager/Treasurer",
        "time_in_position": 8.0,
        "time_with_firm": 8.0
      },
      {
        "name": "Greg Rostecki",
        "position": "Superintendent",
        "time_in_position": 5.0,
        "time_with_firm": 5.0
      },
      {
        "name": "Mike Dianocki",
        "position": "Superintendent",
        "time_in_position": 7.0,
        "time_with_firm": 7.0
      },
      {
        "name": "Chad",
        "position": "Foreman",
        "time_in_position": 5.0,
        "time_with_firm": 5.0
      }
    ],
    "display_name": "Executive Focus",
    "id": "1112145a2f4077220bb11934",
    "name": "executive_focus",
    "type": "sub"
  }
  ```

+ #### Company Structure
