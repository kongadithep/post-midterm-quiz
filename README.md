waiting i'm working on code!!!! it too late T_T
i forgot this part in my git hub because i clone but i forgot to fork , i add answer quiz in edit this file with copy&paste git hub and no time for fork again 
i put a right code in my quiz and i can answer correct you can check it my code answer ,if i forgot since start quiz i can't run answer correct
please add this code to flie data_processing.py  in under this
__location__ = os.path.realpath(
    os.path.join(os.getcwd(), os.path.dirname(__file__)))


this code i forgot to send  T_T 
movie = []
with open(os.path.join(__location__,'movies.csv')) as f:
    rows = csv.DictReader(f)
    for r in rows:
        movie.append(dict(r))  
        
      
