# Ordonnancement-des-Patients-aux-SUA

### Context of the project

Patient scheduling issues in the Emergency Department (ED) can occur at various levels: upstream, intra or downstream. The goal of scheduling is to improve  better organize the Emergency Department.

However, care must be taken when using the term "improve". If we want to reduce waiting time, "improving" simply means making operations faster. If we take the example of a surgical procedure, scheduling will probably make the surgeon work longer and the caregivers work less, whereas in practice, the caregivers are there to reduce the surgeon's intervention time as much as possible. They are necessary and their absence would greatly slow down the progress of e medical task and could even lead to complications. Therefore, we must be precise about the use of scheduling in the ED. The solution we present in this project aims to optimize unnecessary waiting times, such as the primary wait or finding an available bed for a patient, without risking endangering patients by not making decisions on the allocation of medical staff.

In this project, a genetic algorithm is proposed to order patients to the A&E department, and then a list heuristic is proposed to compare their results. Finally, these algorithms are exploited in a multi-agent system (MAS) aiming at simulating interactions between the emergency personnel, in order to optimize patients' order for their care.
Clinical Classification of Emergency patients (CCEP)


In that regard, several criteria have to be taken into consideration : 
  - the the degree of severity of the patients' condition, defined by the Clinical Classification of Emergency Patients (CCEP) 
  - the primary waiting time of patients, i.e. their waiting time during registration and/or while waiting for the primary diagnosis
  - the logical order of medical tasks, i.e. care tasks must not be interchanged


### Recovering the project from Github : 
Create a directory

    $ mkdir git-xpath-engine  
    $ cd git-xpath-engine 
    
Link to the repository of the project

    $ git clone https://github.com/Amal-Chaoui/maxi_project_db
    $ cd maxi_project_db  

Pull changes from the remote repository :

    $ git pull
    
You can run the test in the `unit_tests.py` file by using the following command : 

    $ python3 unit_tests.py
