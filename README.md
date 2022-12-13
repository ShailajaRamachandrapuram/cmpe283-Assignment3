# cmpe283-Assignment3 Instrumentation via hypercall

Student Name:Shailaja Ramachandrapuram

University Name: San Jose State University

Question 1:

Assignment done by myself

Question 2:

Steps:

Compile and build modules by using following commands

#nproc make -j 4 && make -j 4 modules / make -j 2 && make -j 2 modules 

<img width="650" alt="nproc install-a3" src="https://user-images.githubusercontent.com/111623287/207212828-196ae1cc-2cd9-4801-a44a-61cbbfe030bf.PNG">


#sudo apt-get install cpuid

<img width="510" alt="result-a3" src="https://user-images.githubusercontent.com/111623287/207212728-8fec60e3-9cc9-458a-8061-022a97ad2650.PNG">


#Checked dmesg from VM

<img width="1149" alt="exits-a3" src="https://user-images.githubusercontent.com/111623287/207212780-5a89e60d-2267-4300-9d8a-e0272b370012.PNG">

Question 3:

The total exit time is increasing and High 32 bit of total time spent on processing is 0 as time spent in processing exits is very minimal.

Low 32 bit has been captured in %ecx.

The frequency of number of exits are not increasing at a constant rate

We observed 2072028 exits after full boot.

Thank You.
