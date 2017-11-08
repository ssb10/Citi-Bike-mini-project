weekend_trip_avg = weekend_trips.mean()
weekday_trip_avg = weekday_trips.mean()

## Check if Avg_trip_duration(weekend) - Avg_trip_duration(weekday) > 0

if(weekend_trip_avg - weekday_trip_avg) < 0: 
    ##Null cannot be rejected
    print("Null hypothesis cannot be rejected")
else:
    print("Further test need to be performed to test the hypothesis")