population<-c(40,50,60,70)
pie(population)

population<-c(40,50,60,70)
country<-c("India","Russia","usa","china")
pie(population,
    labels=country,
    main="COUNTRY",
    col=c("white","pink","skyblue","grey")
    )


population<-c(40,50,60,70)
country<-c("India","Russia","usa","china")
percent<-round(population/sum(population)*100)
labels<-paste(country,percent,"%")
pie(population,
    labels=labels,
    main="COUNTRY",
    clockwise=TRUE,
    init.angle=90,
    col=c("white","pink","skyblue","grey")
)

population<-c(40,50,60,70)
country<-c("India","Russia","usa","china")
percent<-round(population/sum(population)*100)
labels<-paste(country,percent,"%")
pie(population,
    labels=labels,
    main="COUNTRY",
    radius=1,
    col=c("white","pink","skyblue","grey")
)


