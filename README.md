#program for basic school administration tool import csv
def write_into_csv(info_list)
with open('student_info.csv','a',newline=' ')
          as csv_file:
          writer=csv.writer(csv_file)
          if cdv_file tell()==0:
          	writer.writerrow("name","age","contact no","email id")
          	writer.writerrow(info_list)
          	if__name__=='__main__':
          		condition = True
        while(condition):
        	student_info=input("enter student information in the following format (Name ag contact_no email id"):
        		print(" entered information :" + student_info)
        		#split
        student_info_list = student_info.split(' ')
        print("\n the entered information is \n name: {} \n Age:{} \n contact_no:{} \n email id:{}".format(student_info_list{0},student_info_list{1},student_info_list{2},student_info_list{3}))
        choice_check = input("is the entered information correct?(yes/no): ")
        if choice_check == 'yes':
        	write_info_csv(student_info_list)
       condition_check = input("enter(yes/no) if you want to enter information for another student: ")
       if condition_check == "yes":
       	  condition = True
       elif condition_check == "no":
       	  condition = False
     print("\n please re-enter the values! ")
       	  
