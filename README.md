# learning_R

#box plots
#using ggplot
ggplot(DF, aes(x,y)) + geom_boxplot(colour="blue", fill="red")
ggplotly()
#using qplot
qplot(x,y, data= dataset, geom="boxplot)
