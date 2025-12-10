[
{"fileName": "DIM_DATE.tmdl",
"content": "table DIM_DATE
    lineageTag: d4d9c6e1-7e2c-4e1b-9d7b-0c6b7e4c8d9e
    column DATE_KEY
        dataType: date
        isKey
        summarizeBy: none
        sourceColumn: DATE_KEY
        lineageTag: 7e2c4e1b-9d7b-0c6b-7e4c-8d9ec6e1d4d9
        annotation SummarizationSetBy = Automatic
    column DATE_ID
        dataType: decimal
        summarizeBy: none
        sourceColumn: DATE_ID
        lineageTag: 8d9ec6e1-d4d9-7e2c-4e1b-9d7b0c6b7e4c
        annotation SummarizationSetBy = Automatic
    column DATE_VALUE
        dataType: date
        summarizeBy: none
        sourceColumn: DATE_VALUE
        lineageTag: 9d7b0c6b-7e4c-8d9e-c6e1-d4d97e2c4e1b
        annotation SummarizationSetBy = Automatic
    column YEAR
        dataType: decimal
        summarizeBy: none
        sourceColumn: YEAR
        lineageTag: 0c6b7e4c-8d9e-c6e1-d4d9-7e2c4e1b9d7b
        annotation SummarizationSetBy = Automatic
    column QUARTER
        dataType: decimal
        summarizeBy: none
        sourceColumn: QUARTER
        lineageTag: 1b9d7b0c-6b7e-4c8d-9ec6-e1d4d97e2c4e
        annotation SummarizationSetBy = Automatic
    column MONTH
        dataType: decimal
        summarizeBy: none
        sourceColumn: MONTH
        lineageTag: 2c4e8d9e-c6e1-d4d9-7e2c-4e1b9d7b0c6b
        annotation SummarizationSetBy = Automatic
    column MONTH_NAME
        dataType: string
        summarizeBy: none
        sourceColumn: MONTH_NAME
        lineageTag: 3e1b9d7b-0c6b-7e4c-8d9e-c6e1d4d97e2c
        annotation SummarizationSetBy = Automatic
    column DAY_OF_MONTH
        dataType: decimal
        summarizeBy: none
        sourceColumn: DAY_OF_MONTH
        lineageTag: 4c8d9ec6-e1d4-d97e-2c4e-1b9d7b0c6b7e
        annotation SummarizationSetBy = Automatic
    column DAY_OF_WEEK
        dataType: decimal
        summarizeBy: none
        sourceColumn: DAY_OF_WEEK
        lineageTag: 5e2c4e1b-9d7b-0c6b-7e4c-8d9ec6e1d4d9
        annotation SummarizationSetBy = Automatic
    column DAY_NAME
        dataType: string
        summarizeBy: none
        sourceColumn: DAY_NAME
        lineageTag: 6e1d4d97-e2c4-e1b9-d7b0-c6b7e4c8d9e
        annotation SummarizationSetBy = Automatic
    column IS_WEEKEND
        dataType: boolean
        summarizeBy: none
        sourceColumn: IS_WEEKEND
        lineageTag: 7e4c8d9e-c6e1-d4d9-7e2c-4e1b9d7b0c6b
        annotation SummarizationSetBy = Automatic
    column IS_HOLIDAY
        dataType: boolean
        summarizeBy: none
        sourceColumn: IS_HOLIDAY
        lineageTag: 8d9ec6e1-d4d9-7e2c-4e1b-9d7b0c6b7e4c
        annotation SummarizationSetBy = Automatic
    column FISCAL_YEAR
        dataType: decimal
        summarizeBy: none
        sourceColumn: FISCAL_YEAR
        lineageTag: 9ec6e1d4-d97e-2c4e-1b9d-7b0c6b7e4c8d
        annotation SummarizationSetBy = Automatic
    column FISCAL_QUARTER
        dataType: decimal
        summarizeBy: none
        sourceColumn: FISCAL_QUARTER
        lineageTag: 0c6b7e4c-8d9e-c6e1-d4d9-7e2c4e1b9d7b
        annotation SummarizationSetBy = Automatic
    column WEEK_OF_YEAR
        dataType: decimal
        summarizeBy: none
        sourceColumn: WEEK_OF_YEAR
        lineageTag: 1b9d7b0c-6b7e-4c8d-9ec6-e1d4d97e2c4e
        annotation SummarizationSetBy = Automatic
    column LOAD_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: LOAD_DATE
        lineageTag: 2c4e8d9e-c6e1-d4d9-7e2c-4e1b9d7b0c6b
        annotation SummarizationSetBy = Automatic
    column UPDATE_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: UPDATE_DATE
        lineageTag: 3e1b9d7b-0c6b-7e4c-8d9e-c6e1d4d97e2c
        annotation SummarizationSetBy = Automatic
    column SOURCE_SYSTEM
        dataType: string
        summarizeBy: none
        sourceColumn: SOURCE_SYSTEM
        lineageTag: 4c8d9ec6-e1d4-d97e-2c4e-1b9d7b0c6b7e
        annotation SummarizationSetBy = Automatic
    partition DIM_DATE = m
        mode: import
        source =
            let
                Source = #table({}, {}),
            in 
                Source
    annotation PBI_NavigationStepName = Navigation
    annotation PBI_ResultType = Table"},
... (other table definitions follow here in the same format) ...
]