Roll back Utility:
It is scala plus spark application which rollback data from end of pipeline to initial stage. While progressing it also make backup folder which has orignal data as backup.
We have total 4 staging in pipeline(Data aggregation,Data quality,Data tranformation and Data reconciliation). Application rolls back data from all stages and also removes entries from tables.
