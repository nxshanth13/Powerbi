[
{
  "fileName": "FACT_MEETING_ACTIVITY.tmdl",
  "content": "table FACT_MEETING_ACTIVITY-8b1d7e11-4c2a-4b7b-bd8a-5d6e3a8b0c1a
    lineageTag: 8b1d7e11-4c2a-4b7b-bd8a-5d6e3a8b0c1a
    column MEETING_ACTIVITY_ID
        dataType: int64
        isKey
        summarizeBy: none
        sourceColumn: MEETING_ACTIVITY_ID
        lineageTag: 1d4a2b3c-5e6f-4d8a-9b0c-7f8e9d0a1b2c
        annotation SummarizationSetBy = Automatic
    column USER_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: USER_KEY
        lineageTag: 2e5b6c7d-8a9b-0c1d-2e3f-4a5b6c7d8e9f
        annotation SummarizationSetBy = Automatic
    column MEETING_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: MEETING_KEY
        lineageTag: 3f6a7b8c-9d0e-1f2a-3b4c-5d6e7f8a9b0c
        annotation SummarizationSetBy = Automatic
    column DATE_KEY
        dataType: date
        summarizeBy: none
        sourceColumn: DATE_KEY
        lineageTag: 4a7b8c9d-0e1f-2a3b-4c5d-6e7f8a9b0c1d
        annotation SummarizationSetBy = Automatic
    column FEATURE_KEY
        dataType: string
        summarizeBy: none
        sourceColumn: FEATURE_KEY
        lineageTag: 5b8c9d0e-1f2a-3b4c-5d6e-7f8a9b0c1d2e
        annotation SummarizationSetBy = Automatic
    column MEETING_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: MEETING_DATE
        lineageTag: 6c9d0e1f-2a3b-4c5d-6e7f-8a9b0c1d2e3f
        annotation SummarizationSetBy = Automatic
    column MEETING_TOPIC
        dataType: string
        summarizeBy: none
        sourceColumn: MEETING_TOPIC
        lineageTag: 7d0e1f2a-3b4c-5d6e-7f8a-9b0c1d2e3f4a
        annotation SummarizationSetBy = Automatic
    column START_TIME
        dataType: datetime
        summarizeBy: none
        sourceColumn: START_TIME
        lineageTag: 8e1f2a3b-4c5d-6e7f-8a9b-0c1d2e3f4a5b
        annotation SummarizationSetBy = Automatic
    column END_TIME
        dataType: datetime
        summarizeBy: none
        sourceColumn: END_TIME
        lineageTag: 9f2a3b4c-5d6e-7f8a-9b0c-1d2e3f4a5b6c
        annotation SummarizationSetBy = Automatic
    column DURATION_MINUTES
        dataType: decimal
        summarizeBy: none
        sourceColumn: DURATION_MINUTES
        lineageTag: a03b4c5d-6e7f-8a9b-0c1d-2e3f4a5b6c7d
        annotation SummarizationSetBy = Automatic
    column PARTICIPANT_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: PARTICIPANT_COUNT
        lineageTag: b14c5d6e-7f8a-9b0c-1d2e-3f4a5b6c7d8e
        annotation SummarizationSetBy = Automatic
    column TOTAL_JOIN_TIME_MINUTES
        dataType: decimal
        summarizeBy: none
        sourceColumn: TOTAL_JOIN_TIME_MINUTES
        lineageTag: c25d6e7f-8a9b-0c1d-2e3f-4a5b6c7d8e9f
        annotation SummarizationSetBy = Automatic
    column AVERAGE_PARTICIPATION_MINUTES
        dataType: decimal
        summarizeBy: none
        sourceColumn: AVERAGE_PARTICIPATION_MINUTES
        lineageTag: d36e7f8a-9b0c-1d2e-3f4a-5b6c7d8e9f0a
        annotation SummarizationSetBy = Automatic
    column FEATURES_USED_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: FEATURES_USED_COUNT
        lineageTag: e47f8a9b-0c1d-2e3f-4a5b-6c7d8e9f0a1b
        annotation SummarizationSetBy = Automatic
    column SCREEN_SHARE_USAGE_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: SCREEN_SHARE_USAGE_COUNT
        lineageTag: f58a9b0c-1d2e-3f4a-5b6c-7d8e9f0a1b2c
        annotation SummarizationSetBy = Automatic
    column RECORDING_USAGE_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: RECORDING_USAGE_COUNT
        lineageTag: 061b2c3d-4e5f-6a7b-8c9d-0e1f2a3b4c5d
        annotation SummarizationSetBy = Automatic
    column CHAT_USAGE_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: CHAT_USAGE_COUNT
        lineageTag: 172c3d4e-5f6a-7b8c-9d0e-1f2a3b4c5d6e
        annotation SummarizationSetBy = Automatic
    column MEETING_QUALITY_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: MEETING_QUALITY_SCORE
        lineageTag: 283d4e5f-6a7b-8c9d-0e1f-2a3b4c5d6e7f
        annotation SummarizationSetBy = Automatic
    column AUDIO_QUALITY_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: AUDIO_QUALITY_SCORE
        lineageTag: 394e5f6a-7b8c-9d0e-1f2a-3b4c5d6e7f8a
        annotation SummarizationSetBy = Automatic
    column VIDEO_QUALITY_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: VIDEO_QUALITY_SCORE
        lineageTag: 4a5f6a7b-8c9d-0e1f-2a3b-4c5d6e7f8a9b
        annotation SummarizationSetBy = Automatic
    column CONNECTION_ISSUES_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: CONNECTION_ISSUES_COUNT
        lineageTag: 5b6a7b8c-9d0e-1f2a-3b4c-5d6e7f8a9b0c
        annotation SummarizationSetBy = Automatic
    column MEETING_SATISFACTION_SCORE
        dataType: decimal
        summarizeBy: none
        sourceColumn: MEETING_SATISFACTION_SCORE
        lineageTag: 6c7b8c9d-0e1f-2a3b-4c5d-6e7f8a9b0c1d
        annotation SummarizationSetBy = Automatic
    column PEAK_CONCURRENT_PARTICIPANTS
        dataType: decimal
        summarizeBy: none
        sourceColumn: PEAK_CONCURRENT_PARTICIPANTS
        lineageTag: 7d8c9d0e-1f2a-3b4c-5d6e-7f8a9b0c1d2e
        annotation SummarizationSetBy = Automatic
    column LATE_JOINERS_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: LATE_JOINERS_COUNT
        lineageTag: 8e9d0e1f-2a3b-4c5d-6e7f-8a9b0c1d2e3f
        annotation SummarizationSetBy = Automatic
    column EARLY_LEAVERS_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: EARLY_LEAVERS_COUNT
        lineageTag: 9f0e1f2a-3b4c-5d6e-7f8a-9b0c1d2e3f4a
        annotation SummarizationSetBy = Automatic
    column BREAKOUT_ROOMS_USED
        dataType: decimal
        summarizeBy: none
        sourceColumn: BREAKOUT_ROOMS_USED
        lineageTag: a01f2a3b-4c5d-6e7f-8a9b-0c1d2e3f4a5b
        annotation SummarizationSetBy = Automatic
    column POLLS_CONDUCTED
        dataType: decimal
        summarizeBy: none
        sourceColumn: POLLS_CONDUCTED
        lineageTag: b12a3b4c-5d6e-7f8a-9b0c-1d2e3f4a5b6c
        annotation SummarizationSetBy = Automatic
    column FILE_SHARES_COUNT
        dataType: decimal
        summarizeBy: none
        sourceColumn: FILE_SHARES_COUNT
        lineageTag: c23b4c5d-6e7f-8a9b-0c1d-2e3f4a5b6c7d
        annotation SummarizationSetBy = Automatic
    column LOAD_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: LOAD_DATE
        lineageTag: d34c5d6e-7f8a-9b0c-1d2e-3f4a5b6c7d8e
        annotation SummarizationSetBy = Automatic
    column UPDATE_DATE
        dataType: date
        summarizeBy: none
        sourceColumn: UPDATE_DATE
        lineageTag: e45d6e7f-8a9b-0c1d-2e3f-4a5b6c7d8e9f
        annotation SummarizationSetBy = Automatic
    column SOURCE_SYSTEM
        dataType: string
        summarizeBy: none
        sourceColumn: SOURCE_SYSTEM
        lineageTag: f56e7f8a-9b0c-1d2e-3f4a-5b6c7d8e9f0a
        annotation SummarizationSetBy = Automatic
    partition FACT_MEETING_ACTIVITY = m
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