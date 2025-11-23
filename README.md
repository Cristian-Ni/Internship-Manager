[Project.md](https://github.com/user-attachments/files/22983109/Project.md)
# Cerințe proiect
- Experiență utilizator:
    - 3 tipuri utilizatori:
      - Studenți:
        - caută locuri de practică (Search option)
        - aplică pt locuri de practică (Pot uploada CV-ul) (câmpuri formular de stabilit)
        - pot primi notificări lrgate de practică (note, admis/respins)
        - dacă e acceptat pt o poziție, toate cererile sunt retrase iar locurile de practică la alte
          companii se  eliberează

      - Companii
        - postează anunțuri practică (anunțurile  sunt valabile  până la sfârșitul perioadei de înscriere determinată de deartament)
        - determină dacă studentul e admis sau respins
        - dau note studenților la practică
      
      - Departament
        - setează deadline-ul pt înscrieri la practică
        - moderează conturile companiilor
          - poate șterge conturi ale companiilor
          - aprobă anunțuri oferte practică
        - creează conturi studenți importând o listă cu studenți 
        - asignează  studenții fără practică pe poziții  de practică la facultate
        - văd rezultatele interview-urilor
        - pot vedea și exporta notele


# Strucură frontend

## Student
- Homepage
      - personal info
          - username
          - CV.pdf(optional)
          - Dep
          - Year
     - Internships he applied for + status

- Inernship list
      - Internship page
          - Requirements
          - Nr of available seats
          - Due date for new applications
          - Status (pending acceptance interview/seat, application accepted/declined, seats available/not available)
            (optional)
          - button to application form


## Dep Rep
- Homepage
  - faculty positions
- Companies page
  - Company list + vetting status
    - Company page
      - Company info
      - Internship position list + vetting status
- Student page
  - Student list
    - Employment status
    - Grade
  - Export to excel button
- Faculy positions page
  - Faculty positions list
    - Faculty positions page
      -Student list
       - Grade + ability to edit grade

## Comp rep
- Homepage
  - Basic company info
- Internships page (can only see internships posted by him)
  - Add internship button
  - Inernship list
      - Internship page
          - Requirements
          - Nr of available seats
          - Due date for new applications
          - List of students
                - Student info (mentioned at student section)
                - Application status
                - add grade (once employed)


## Page templates
- Homepage
- List page
      - Comps
      - Students
      - Internships
- Info page
      - Use Homepage template for students
      - Internship
      - Use Homepage template for companies
