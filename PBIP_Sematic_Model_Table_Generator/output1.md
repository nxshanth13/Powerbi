[
{
  "fileName": "DIM_DATE.tmdl",
  "content": "table DIM_DATE
    lineageTag: 2eeb4e5f-3e3e-4a7e-8b2f-6b2c7b1a9cde
    column DATE_KEY
        dataType: date
        isKey
        summarizeBy: none
        sourceColumn: DATE_KEY
        lineageTag: 1c1c2a7e-0a5b-45a9-9a2c-3a7e5b8c2f1d
        annotation SummarizationSetBy = Automatic
    column DATE_ID
        dataType: decimal
        summarizeBy: none
        sourceColumn: DATE_ID
        lineageTag: 2a7e5b1c-3c2a-4e5f-8b2f-6b2c7b1a9cdf
        annotation SummarizationSetBy = Automatic
    column DATE_VALUE
        dataType: date
        summarizeBy: none
        sourceColumn: DATE_VALUE
        lineageTag: 3e5f2a7e-1c1c-4a7e-8b2f-6b2c7b1a9cd1
        annotation SummarizationSetBy = Automatic
    column YEAR
        dataType: decimal
        summarizeBy: none
        sourceColumn: YEAR
        lineageTag: 4a7e2a7e-1c1c-4e5f-9a2c-6b2c7b1a9cd2
        annotation SummarizationSetBy = Automatic
    column QUARTER
        dataType: decimal
        summarizeBy: none
        sourceColumn: QUARTER
        lineageTag: 5b8c2a7e-1c1c-4a7e-8b2f-7b2c7b1a9cd3
        annotation SummarizationSetBy = Automatic
    column MONTH
        dataType: decimal
        summarizeBy: none
        sourceColumn: MONTH
        lineageTag: 6c2a2a7e-1c1c-4e5f-8b2f-8b2c7b1a9cd4
        annotation SummarizationSetBy = Automatic
    column MONTH_NAME
        dataType: string
        summarizeBy: none
        sourceColumn: MONTH_NAME
        lineageTag: 7d1c2a7e-1c1c-4a7e-8b2f-9b2c7b1a9cd5
        annotation SummarizationSetBy = Automatic
    column DAY_OF_MONTH
        dataType: decimal
        summarizeBy: none
        sourceColumn: DAY_OF_MONTH
        lineageTag: 8e1c2a7e-1c1c-4e5f-8b2f-ab2c7b1a9cd6
        annotation SummarizationSetBy = Automatic
    column DAY_OF_WEEK
        dataType: decimal
        summarizeBy: none
        sourceColumn: DAY_OF_WEEK
        lineageTag: 9f1c2a7e-1c1c-4a7e-8b2f-bb2c7b1a9cd7
        annotation SummarizationSetBy = Automatic
    column DAY_NAME
        dataType: string
        summarizeBy: none
        sourceColumn: DAY_NAME
        lineageTag: af1c2a7e-1c1c-4e5f-8b2f-cb2c7b1a9cd8
        annotation SummarizationSetBy = Automatic
    column IS_WEEKEND
        dataType: boolean
        summarizeBy: none
        sourceColumn: IS_WEEKEND
        lineageTag: bf1c2a7e-1c1c-4a7e-8b2f-db2c7b1a9cd9
        annotation SummarizationSetBy = Automatic
    column IS_HOLIDAY
        dataType: boolean
        summarizeBy: none
        sourceColumn: IS_HOLIDAY
        lineageTag: cf1c2a7e-1c1c-4e5f-8b2f-eb2c7b1a9cda
        annotation SummarizationSetBy = Automatic
    column FISCAL_YEAR
        dataType: decimal
        summarizeBy: none
        sourceColumn: FISCAL_YEAR
        lineageTag: df1c2a7e-1c1c-4a7e-8b2f-fb2c7b1a9cdb
        annotation SummarizationSetBy = Automatic
    column FISCAL_QUARTER
        dataType: decimal
        summarizeBy: none
        sourceColumn: FISCAL_QUARTER
        lineageTag: ef1c2a7e-1c1c-4e5f-8b2f-0b2c7b1a9cdc
        annotation SummarizationSetBy = Automatic
    column WEEK_OF_YEAR
        dataType: decimal
        summarizeBy: none
        sourceColumn: WEEK_OF_YEAR
        lineageTag: ff1c2a7e-1c1c-4a7e-8b2f-1b2c7b1a9cdd
        annotation SummarizationSetBy = Automatic
    column LOAD_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: LOAD_DATE
        lineageTag: 0f1c2a7e-1c1c-4e5f-8b2f-2b2c7b1a9cde
        annotation SummarizationSetBy = Automatic
    column UPDATE_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: UPDATE_DATE
        lineageTag: 1f1c2a7e-1c1c-4a7e-8b2f-3b2c7b1a9cdf
        annotation SummarizationSetBy = Automatic
    column SOURCE_SYSTEM
        dataType: string
        summarizeBy: none
        sourceColumn: SOURCE_SYSTEM
        lineageTag: 2f1c2a7e-1c1c-4e5f-8b2f-4b2c7b1a9ce0
        annotation SummarizationSetBy = Automatic
    partition DIM_DATE = m
        mode: import
        source =
            let
                Source = #table({}, {}),
            in 
                Source
    annotation PBI_NavigationStepName = Navigation
    annotation PBI_ResultType = Table"
},
{
  "fileName": "DIM_FEATURE.tmdl",
  "content": "table DIM_FEATURE
    lineageTag: 3b5e7f2d-4e1a-4e1b-9f2c-4a7e5b8c2f1d
    column FEATURE_KEY
        dataType: string
        isKey
        summarizeBy: none
        sourceColumn: FEATURE_KEY
        lineageTag: 4c1d2b7e-2c5b-45a9-9a2c-3a7e5b8c2f1e
        annotation SummarizationSetBy = Automatic
    column FEATURE_ID
        dataType: decimal
        summarizeBy: none
        sourceColumn: FEATURE_ID
        lineageTag: 5d2e3c8f-3c2a-4e5f-8b2f-6b2c7b1a9ce1
        annotation SummarizationSetBy = Automatic
    column FEATURE_NAME
        dataType: string
        summarizeBy: none
        sourceColumn: FEATURE_NAME
        lineageTag: 6e3f4d9a-1c1c-4a7e-8b2f-7b2c7b1a9ce2
        annotation SummarizationSetBy = Automatic
    column FEATURE_CATEGORY
        dataType: string
        summarizeBy: none
        sourceColumn: FEATURE_CATEGORY
        lineageTag: 7f4g5eab-1c1c-4e5f-9a2c-8b2c7b1a9ce3
        annotation SummarizationSetBy = Automatic
    column FEATURE_TYPE
        dataType: string
        summarizeBy: none
        sourceColumn: FEATURE_TYPE
        lineageTag: 8g5h6fbc-1c1c-4a7e-8b2f-9b2c7b1a9ce4
        annotation SummarizationSetBy = Automatic
    column FEATURE_COMPLEXITY
        dataType: string
        summarizeBy: none
        sourceColumn: FEATURE_COMPLEXITY
        lineageTag: 9h6i7gcd-1c1c-4e5f-8b2f-ab2c7b1a9ce5
        annotation SummarizationSetBy = Automatic
    column IS_PREMIUM_FEATURE
        dataType: boolean
        summarizeBy: none
        sourceColumn: IS_PREMIUM_FEATURE
        lineageTag: ai7j8hde-1c1c-4a7e-8b2f-bb2c7b1a9ce6
        annotation SummarizationSetBy = Automatic
    column FEATURE_RELEASE_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: FEATURE_RELEASE_DATE
        lineageTag: bj8k9ief-1c1c-4e5f-8b2f-cb2c7b1a9ce7
        annotation SummarizationSetBy = Automatic
    column FEATURE_STATUS
        dataType: string
        summarizeBy: none
        sourceColumn: FEATURE_STATUS
        lineageTag: ck9l0jfg-1c1c-4a7e-8b2f-db2c7b1a9ce8
        annotation SummarizationSetBy = Automatic
    column USAGE_FREQUENCY_CATEGORY
        dataType: string
        summarizeBy: none
        sourceColumn: USAGE_FREQUENCY_CATEGORY
        lineageTag: dl0m1khg-1c1c-4e5f-8b2f-eb2c7b1a9ce9
        annotation SummarizationSetBy = Automatic
    column FEATURE_DESCRIPTION
        dataType: string
        summarizeBy: none
        sourceColumn: FEATURE_DESCRIPTION
        lineageTag: em1n2lig-1c1c-4a7e-8b2f-fb2c7b1a9cea
        annotation SummarizationSetBy = Automatic
    column TARGET_USER_SEGMENT
        dataType: string
        summarizeBy: none
        sourceColumn: TARGET_USER_SEGMENT
        lineageTag: fn2o3mjh-1c1c-4e5f-8b2f-0b2c7b1a9ceb
        annotation SummarizationSetBy = Automatic
    column LOAD_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: LOAD_DATE
        lineageTag: go3p4nki-1c1c-4a7e-8b2f-1b2c7b1a9cec
        annotation SummarizationSetBy = Automatic
    column UPDATE_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: UPDATE_DATE
        lineageTag: hp4q5olj-1c1c-4e5f-8b2f-2b2c7b1a9ced
        annotation SummarizationSetBy = Automatic
    column SOURCE_SYSTEM
        dataType: string
        summarizeBy: none
        sourceColumn: SOURCE_SYSTEM
        lineageTag: iq5r6pmk-1c1c-4a7e-8b2f-3b2c7b1a9cee
        annotation SummarizationSetBy = Automatic
    partition DIM_FEATURE = m
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