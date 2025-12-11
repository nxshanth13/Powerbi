[
{
  "fileName": "FACT_REVENUE_ACTIVITY.tmdl",
  "content": "table FACT_REVENUE_ACTIVITY-8c4a0d5e-3f5e-4e9a-8b7c-4f7e1d3f2f09
    lineageTag: 8c4a0d5e-3f5e-4e9a-8b7c-4f7e1d3f2f09
    column REVENUE_ACTIVITY_ID
        dataType: decimal
        isKey
        summarizeBy: none
        sourceColumn: REVENUE_ACTIVITY_ID
        lineageTag: 3bfcf1ae-7e9b-4d6c-9b2d-3e2a2d5c1e01
        annotation SummarizationSetBy = Automatic
    column USER_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: USER_KEY
        lineageTag: 0e3d0f8c-8e3a-4e1a-b2d1-7c6e7d1f8e02
        annotation SummarizationSetBy = Automatic
    column LICENSE_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: LICENSE_KEY
        lineageTag: 1f4e0d3c-6e7b-4c1a-9d2b-7e3f1d4c8e03
        annotation SummarizationSetBy = Automatic
    column DATE_KEY
        dataType: date
        summarizeBy: none
        sourceColumn: DATE_KEY
        lineageTag: 2e5d1f3b-7c8a-4e2b-8d1c-3f7e1d4b5e04
        annotation SummarizationSetBy = Automatic
    column TRANSACTION_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: TRANSACTION_DATE
        lineageTag: 3d6e2f4a-8c7b-4e3c-9d2a-1e7f2d4c6e05
        annotation SummarizationSetBy = Automatic
    column EVENT_TYPE
        dataType: string
        summarizeBy: none
        sourceColumn: EVENT_TYPE
        lineageTag: 4e7f3d5b-9c8a-4e4b-8d3c-2f8e3d5b7e06
        annotation SummarizationSetBy = Automatic
    column AMOUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: AMOUNT
        lineageTag: 5f8e4d6c-1a9b-4e5c-8d4b-3f9e4d6b8e07
        annotation SummarizationSetBy = Automatic
    column CURRENCY
        dataType: string
        summarizeBy: none
        sourceColumn: CURRENCY
        lineageTag: 6e9f5d7b-2b1a-4e6c-9d5b-4f1e5d7c9e08
        annotation SummarizationSetBy = Automatic
    column PAYMENT_METHOD
        dataType: string
        summarizeBy: none
        sourceColumn: PAYMENT_METHOD
        lineageTag: 7f1e6d8c-3a2b-4e7c-8d6b-5f2e6d8c1e09
        annotation SummarizationSetBy = Automatic
    column SUBSCRIPTION_REVENUE_AMOUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: SUBSCRIPTION_REVENUE_AMOUNT
        lineageTag: 8e2f7d9b-4b3a-4e8c-9d7b-6f3e7d9b2e10
        annotation SummarizationSetBy = Automatic
    column ONE_TIME_REVENUE_AMOUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: ONE_TIME_REVENUE_AMOUNT
        lineageTag: 9f3e8d1c-5a4b-4e9c-8d8b-7f4e8d1c3e11
        annotation SummarizationSetBy = Automatic
    column REFUND_AMOUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: REFUND_AMOUNT
        lineageTag: 1a4e9d2b-6b5a-4e1c-9d9b-8f5e9d2b4e12
        annotation SummarizationSetBy = Automatic
    column TAX_AMOUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: TAX_AMOUNT
        lineageTag: 2b5e1d3c-7c6b-4e2c-8d1b-9f6e1d3c5e13
        annotation SummarizationSetBy = Automatic
    column NET_REVENUE_AMOUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: NET_REVENUE_AMOUNT
        lineageTag: 3c6e2d4b-8b7a-4e3c-9d2b-1f7e2d4b6e14
        annotation SummarizationSetBy = Automatic
    column DISCOUNT_AMOUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: DISCOUNT_AMOUNT
        lineageTag: 4d7e3c5a-9c8b-4e4c-8d3b-2f8e3c5a7e15
        annotation SummarizationSetBy = Automatic
    column EXCHANGE_RATE
        dataType: decimal
        summarizeBy: none
        sourceColumn: EXCHANGE_RATE
        lineageTag: 5e8f4d6b-1a9c-4e5d-8d4c-3f9e4d6b8e16
        annotation SummarizationSetBy = Automatic
    column USD_AMOUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: USD_AMOUNT
        lineageTag: 6f9e5d7c-2b1b-4e6d-9d5c-4f1e5d7c9e17
        annotation SummarizationSetBy = Automatic
    column SUBSCRIPTION_PERIOD_MONTHS
        dataType: decimal
        summarizeBy: none
        sourceColumn: SUBSCRIPTION_PERIOD_MONTHS
        lineageTag: 7a1e6d8b-3a2c-4e7d-8d6c-5f2e6d8b1e18
        annotation SummarizationSetBy = Automatic
    column LICENSE_QUANTITY
        dataType: decimal
        summarizeBy: none
        sourceColumn: LICENSE_QUANTITY
        lineageTag: 8b2f7d9c-4b3b-4e8d-9d7c-6f3e7d9c2e19
        annotation SummarizationSetBy = Automatic
    column PRORATION_AMOUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: PRORATION_AMOUNT
        lineageTag: 9c3e8d1b-5a4c-4e9d-8d8c-7f4e8d1b3e20
        annotation SummarizationSetBy = Automatic
    column COMMISSION_AMOUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: COMMISSION_AMOUNT
        lineageTag: 1d4e9c2a-6b5b-4e1d-9d9c-8f5e9c2a4e21
        annotation SummarizationSetBy = Automatic
    column MRR_IMPACT
        dataType: decimal
        summarizeBy: none
        sourceColumn: MRR_IMPACT
        lineageTag: 2e5e1c3b-7c6c-4e2d-8d1c-9f6e1c3b5e22
        annotation SummarizationSetBy = Automatic
    column ARR_IMPACT
        dataType: decimal
        summarizeBy: none
        sourceColumn: ARR_IMPACT
        lineageTag: 3f6e2b4c-8b7b-4e3d-9d2c-1f7e2b4c6e23
        annotation SummarizationSetBy = Automatic
    column CUSTOMER_LIFETIME_VALUE
        dataType: decimal
        summarizeBy: none
        sourceColumn: CUSTOMER_LIFETIME_VALUE
        lineageTag: 4a7e3d5b-9c8c-4e4d-8d3c-2f8e3d5b7e24
        annotation SummarizationSetBy = Automatic
    column CHURN_RISK_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: CHURN_RISK_SCORE
        lineageTag: 5b8e4c6d-1a9d-4e5e-8d4d-3f9e4c6d8e25
        annotation SummarizationSetBy = Automatic
    column PAYMENT_STATUS
        dataType: string
        summarizeBy: none
        sourceColumn: PAYMENT_STATUS
        lineageTag: 6c9f5e7d-2b1c-4e6e-9d5d-4f1e5e7d9e26
        annotation SummarizationSetBy = Automatic
    column REFUND_REASON
        dataType: string
        summarizeBy: none
        sourceColumn: REFUND_REASON
        lineageTag: 7d1e6c8b-3a2d-4e7e-8d6d-5f2e6c8b1e27
        annotation SummarizationSetBy = Automatic
    column SALES_CHANNEL
        dataType: string
        summarizeBy: none
        sourceColumn: SALES_CHANNEL
        lineageTag: 8e2f7c9d-4b3c-4e8e-9d7d-6f3e7c9d2e28
        annotation SummarizationSetBy = Automatic
    column PROMOTION_CODE
        dataType: string
        summarizeBy: none
        sourceColumn: PROMOTION_CODE
        lineageTag: 9f3e8c1d-5a4d-4e9e-8d8d-7f4e8c1d3e29
        annotation SummarizationSetBy = Automatic
    column LOAD_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: LOAD_DATE
        lineageTag: 1a4e9b2c-6b5c-4e1e-9d9d-8f5e9b2c4e30
        annotation SummarizationSetBy = Automatic
    column UPDATE_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: UPDATE_DATE
        lineageTag: 2b5e1c3d-7c6d-4e2e-8d1d-9f6e1c3d5e31
        annotation SummarizationSetBy = Automatic
    column SOURCE_SYSTEM
        dataType: string
        summarizeBy: none
        sourceColumn: SOURCE_SYSTEM
        lineageTag: 3c6e2d4e-8b7c-4e3e-9d2d-1f7e2d4e6e32
        annotation SummarizationSetBy = Automatic
    partition FACT_REVENUE_ACTIVITY = m
        mode: import
        source =
            let
                Source = #table({}, {}),
            in 
                Source
    annotation PBI_NavigationStepName = Navigation
    annotation PBI_ResultType = Table"
}
]