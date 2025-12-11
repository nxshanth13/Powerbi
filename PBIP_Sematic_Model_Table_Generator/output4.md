[
{
  "fileName": "FACT_FEATURE_USAGE.tmdl",
  "content": "table FACT_FEATURE_USAGE-0e0a8d9b-6b55-4a2d-8c9f-1f8b9e7c2a01
    lineageTag: 0e0a8d9b-6b55-4a2d-8c9f-1f8b9e7c2a01
    column FEATURE_USAGE_ID
        dataType: int64
        isKey
        summarizeBy: none
        sourceColumn: FEATURE_USAGE_ID
        lineageTag: 7c9e8b1f-2d4a-5b6c-7e8f-9a0b1c2d3e01
        annotation SummarizationSetBy = Automatic
    column DATE_KEY
        dataType: date
        summarizeBy: none
        sourceColumn: DATE_KEY
        lineageTag: 8b9e7c1f-2a3d-4c5e-6f7a-8b9c0d1e2f01
        annotation SummarizationSetBy = Automatic
    column FEATURE_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: FEATURE_KEY
        lineageTag: 9e7c1f8b-2a4d-5c6e-7f8a-9b0c1d2e3f01
        annotation SummarizationSetBy = Automatic
    column USER_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: USER_KEY
        lineageTag: 1f8b9e7c-2a3d-4c5e-6f7a-8b9c0d1e2f02
        annotation SummarizationSetBy = Automatic
    column MEETING_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: MEETING_KEY
        lineageTag: 2a3d4c5e-6f7a-8b9c-0d1e-2f3a4b5c6d01
        annotation SummarizationSetBy = Automatic
    column USAGE_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: USAGE_DATE
        lineageTag: 3d4c5e6f-7a8b-9c0d-1e2f-3a4b5c6d7e01
        annotation SummarizationSetBy = Automatic
    column USAGE_TIMESTAMP
        dataType: datetime
        summarizeBy: none
        sourceColumn: USAGE_TIMESTAMP
        lineageTag: 4c5e6f7a-8b9c-0d1e-2f3a-4b5c6d7e8f01
        annotation SummarizationSetBy = Automatic
    column FEATURE_NAME
        dataType: string
        summarizeBy: none
        sourceColumn: FEATURE_NAME
        lineageTag: 5e6f7a8b-9c0d-1e2f-3a4b-5c6d7e8f9a01
        annotation SummarizationSetBy = Automatic
    column USAGE_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: USAGE_COUNT
        lineageTag: 6f7a8b9c-0d1e-2f3a-4b5c-6d7e8f9a0b01
        annotation SummarizationSetBy = Automatic
    column USAGE_DURATION_MINUTES
        dataType: decimal
        summarizeBy: none
        sourceColumn: USAGE_DURATION_MINUTES
        lineageTag: 7a8b9c0d-1e2f-3a4b-5c6d-7e8f9a0b1c01
        annotation SummarizationSetBy = Automatic
    column SESSION_DURATION_MINUTES
        dataType: decimal
        summarizeBy: none
        sourceColumn: SESSION_DURATION_MINUTES
        lineageTag: 8b9c0d1e-2f3a-4b5c-6d7e-8f9a0b1c2d01
        annotation SummarizationSetBy = Automatic
    column FEATURE_ADOPTION_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: FEATURE_ADOPTION_SCORE
        lineageTag: 9c0d1e2f-3a4b-5c6d-7e8f-9a0b1c2d3e01
        annotation SummarizationSetBy = Automatic
    column USER_EXPERIENCE_RATING
        dataType: decimal
        summarizeBy: none
        sourceColumn: USER_EXPERIENCE_RATING
        lineageTag: 0d1e2f3a-4b5c-6d7e-8f9a-0b1c2d3e4f01
        annotation SummarizationSetBy = Automatic
    column FEATURE_PERFORMANCE_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: FEATURE_PERFORMANCE_SCORE
        lineageTag: 1e2f3a4b-5c6d-7e8f-9a0b-1c2d3e4f5a01
        annotation SummarizationSetBy = Automatic
    column CONCURRENT_FEATURES_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: CONCURRENT_FEATURES_COUNT
        lineageTag: 2f3a4b5c-6d7e-8f9a-0b1c-2d3e4f5a6b01
        annotation SummarizationSetBy = Automatic
    column USAGE_CONTEXT
        dataType: string
        summarizeBy: none
        sourceColumn: USAGE_CONTEXT
        lineageTag: 3a4b5c6d-7e8f-9a0b-1c2d-3e4f5a6b7c01
        annotation SummarizationSetBy = Automatic
    column DEVICE_TYPE
        dataType: string
        summarizeBy: none
        sourceColumn: DEVICE_TYPE
        lineageTag: 4b5c6d7e-8f9a-0b1c-2d3e-4f5a6b7c8d01
        annotation SummarizationSetBy = Automatic
    column PLATFORM_VERSION
        dataType: string
        summarizeBy: none
        sourceColumn: PLATFORM_VERSION
        lineageTag: 5c6d7e8f-9a0b-1c2d-3e4f-5a6b7c8d9e01
        annotation SummarizationSetBy = Automatic
    column ERROR_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: ERROR_COUNT
        lineageTag: 6d7e8f9a-0b1c-2d3e-4f5a-6b7c8d9e0f01
        annotation SummarizationSetBy = Automatic
    column SUCCESS_RATE
        dataType: decimal
        summarizeBy: none
        sourceColumn: SUCCESS_RATE
        lineageTag: 7e8f9a0b-1c2d-3e4f-5a6b-7c8d9e0f1a01
        annotation SummarizationSetBy = Automatic
    column LOAD_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: LOAD_DATE
        lineageTag: 8f9a0b1c-2d3e-4f5a-6b7c-8d9e0f1a2b01
        annotation SummarizationSetBy = Automatic
    column UPDATE_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: UPDATE_DATE
        lineageTag: 9a0b1c2d-3e4f-5a6b-7c8d-9e0f1a2b3c01
        annotation SummarizationSetBy = Automatic
    column SOURCE_SYSTEM
        dataType: string
        summarizeBy: none
        sourceColumn: SOURCE_SYSTEM
        lineageTag: 0b1c2d3e-4f5a-6b7c-8d9e-0f1a2b3c4d01
        annotation SummarizationSetBy = Automatic
    partition FACT_FEATURE_USAGE = m
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
  "fileName": "FACT_MEETING_ACTIVITY.tmdl",
  "content": "table FACT_MEETING_ACTIVITY-1f2e3d4c-5b6a-7c8d-9e0f-1a2b3c4d5e01
    lineageTag: 1f2e3d4c-5b6a-7c8d-9e0f-1a2b3c4d5e01
    column MEETING_ACTIVITY_ID
        dataType: int64
        isKey
        summarizeBy: none
        sourceColumn: MEETING_ACTIVITY_ID
        lineageTag: 2e3d4c5b-6a7c-8d9e-0f1a-2b3c4d5e6f01
        annotation SummarizationSetBy = Automatic
    column USER_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: USER_KEY
        lineageTag: 3d4c5b6a-7c8d-9e0f-1a2b-3c4d5e6f7a01
        annotation SummarizationSetBy = Automatic
    column MEETING_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: MEETING_KEY
        lineageTag: 4c5b6a7c-8d9e-0f1a-2b3c-4d5e6f7a8b01
        annotation SummarizationSetBy = Automatic
    column DATE_KEY
        dataType: date
        summarizeBy: none
        sourceColumn: DATE_KEY
        lineageTag: 5b6a7c8d-9e0f-1a2b-3c4d-5e6f7a8b9c01
        annotation SummarizationSetBy = Automatic
    column FEATURE_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: FEATURE_KEY
        lineageTag: 6a7c8d9e-0f1a-2b3c-4d5e-6f7a8b9c0d01
        annotation SummarizationSetBy = Automatic
    column MEETING_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: MEETING_DATE
        lineageTag: 7c8d9e0f-1a2b-3c4d-5e6f-7a8b9c0d1e01
        annotation SummarizationSetBy = Automatic
    column MEETING_TOPIC
        dataType: string
        summarizeBy: none
        sourceColumn: MEETING_TOPIC
        lineageTag: 8d9e0f1a-2b3c-4d5e-6f7a-8b9c0d1e2f01
        annotation SummarizationSetBy = Automatic
    column START_TIME
        dataType: datetime
        summarizeBy: none
        sourceColumn: START_TIME
        lineageTag: 9e0f1a2b-3c4d-5e6f-7a8b-9c0d1e2f3a01
        annotation SummarizationSetBy = Automatic
    column END_TIME
        dataType: datetime
        summarizeBy: none
        sourceColumn: END_TIME
        lineageTag: 0f1a2b3c-4d5e-6f7a-8b9c-0d1e2f3a4b01
        annotation SummarizationSetBy = Automatic
    column DURATION_MINUTES
        dataType: decimal
        summarizeBy: none
        sourceColumn: DURATION_MINUTES
        lineageTag: 1a2b3c4d-5e6f-7a8b-9c0d-1e2f3a4b5c01
        annotation SummarizationSetBy = Automatic
    column PARTICIPANT_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: PARTICIPANT_COUNT
        lineageTag: 2b3c4d5e-6f7a-8b9c-0d1e-2f3a4b5c6d01
        annotation SummarizationSetBy = Automatic
    column TOTAL_JOIN_TIME_MINUTES
        dataType: decimal
        summarizeBy: none
        sourceColumn: TOTAL_JOIN_TIME_MINUTES
        lineageTag: 3c4d5e6f-7a8b-9c0d-1e2f-3a4b5c6d7e01
        annotation SummarizationSetBy = Automatic
    column AVERAGE_PARTICIPATION_MINUTES
        dataType: decimal
        summarizeBy: none
        sourceColumn: AVERAGE_PARTICIPATION_MINUTES
        lineageTag: 4d5e6f7a-8b9c-0d1e-2f3a-4b5c6d7e8f01
        annotation SummarizationSetBy = Automatic
    column FEATURES_USED_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: FEATURES_USED_COUNT
        lineageTag: 5e6f7a8b-9c0d-1e2f-3a4b-5c6d7e8f9a01
        annotation SummarizationSetBy = Automatic
    column SCREEN_SHARE_USAGE_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: SCREEN_SHARE_USAGE_COUNT
        lineageTag: 6f7a8b9c-0d1e-2f3a-4b5c-6d7e8f9a0b02
        annotation SummarizationSetBy = Automatic
    column RECORDING_USAGE_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: RECORDING_USAGE_COUNT
        lineageTag: 7a8b9c0d-1e2f-3a4b-5c6d-7e8f9a0b1c02
        annotation SummarizationSetBy = Automatic
    column CHAT_USAGE_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: CHAT_USAGE_COUNT
        lineageTag: 8b9c0d1e-2f3a-4b5c-6d7e-8f9a0b1c2d02
        annotation SummarizationSetBy = Automatic
    column MEETING_QUALITY_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: MEETING_QUALITY_SCORE
        lineageTag: 9c0d1e2f-3a4b-5c6d-7e8f-9a0b1c2d3e02
        annotation SummarizationSetBy = Automatic
    column AUDIO_QUALITY_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: AUDIO_QUALITY_SCORE
        lineageTag: 0d1e2f3a-4b5c-6d7e-8f9a-0b1c2d3e4f02
        annotation SummarizationSetBy = Automatic
    column VIDEO_QUALITY_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: VIDEO_QUALITY_SCORE
        lineageTag: 1e2f3a4b-5c6d-7e8f-9a0b-1c2d3e4f5a02
        annotation SummarizationSetBy = Automatic
    column CONNECTION_ISSUES_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: CONNECTION_ISSUES_COUNT
        lineageTag: 2f3a4b5c-6d7e-8f9a-0b1c-2d3e4f5a6b02
        annotation SummarizationSetBy = Automatic
    column MEETING_SATISFACTION_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: MEETING_SATISFACTION_SCORE
        lineageTag: 3a4b5c6d-7e8f-9a0b-1c2d-3e4f5a6b7c02
        annotation SummarizationSetBy = Automatic
    column PEAK_CONCURRENT_PARTICIPANTS
        dataType: decimal
        summarizeBy: none
        sourceColumn: PEAK_CONCURRENT_PARTICIPANTS
        lineageTag: 4b5c6d7e-8f9a-0b1c-2d3e-4f5a6b7c8d02
        annotation SummarizationSetBy = Automatic
    column LATE_JOINERS_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: LATE_JOINERS_COUNT
        lineageTag: 5c6d7e8f-9a0b-1c2d-3e4f-5a6b7c8d9e02
        annotation SummarizationSetBy = Automatic
    column EARLY_LEAVERS_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: EARLY_LEAVERS_COUNT
        lineageTag: 6d7e8f9a-0b1c-2
