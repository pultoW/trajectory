# trajectory
This is the “Data Availability” statement for "Deep Learning-based Service Scheduling Mechanism for Green RSUs in the IoVs".

The original data is the GPS data of taxis in Shenzhen, China, which is continuously sampled by the GPS devices during time period 2011/04/18 - 2011/04/26.



Considering the large amount of original data(about 10G), the processed data is submitted here(trajetroy.pkl).



If you want to view the data, it is advised to use the Python3 satement "with open(./trajectory.pkl,'rb')as file:return pickle.load(file)".



The "trajectory.pkl" is stored in dictionray format:

{day:{vehilce:(day,number):[(interval,(grid))]}

day: the i-th day, range is 1-9

vehicle: the vehicle ID

number: the j-th trajectory of a day

interval: the time slot, range is 1-97

grid: RSU's 2D coordinate



A complete example of is as follows: 

1:{1:{(1, 1): [(29, (43, 18)), (29, (42, 18)), (29, (42, 19)),...]}}}.



If you have any questions, you can contact me via ljt_IT@163.com.

