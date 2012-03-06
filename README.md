# Most Basic Steps:
1. Clone this repository
3. Run: 'gradle init'
4. Gripes will update your build.gradle file, edit the gripes{} section accordingly
5. Run: 'gradle setup'

# To Create Models and ActionBeans:
5. First entity class: 'gradle create -Pmodel=Page'
6. Edit the entity, adding properties (i.e. String name, description)
7. Create actions: 'gradle create -Paction=Page'
8. Run the app: 'gradle run'
9. Browse: http://localhost:8888/gripes