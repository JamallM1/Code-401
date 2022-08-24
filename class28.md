## Django Forms
- used for taking input from the user in some manner and using that information for logical operations on databases
- forms and models share the same field types
- Django form fields define two types of functionality, a form field's HTML markup and its server-side validation facilities. 

# <form action="/team_name_url/" method="post">
    <label for="team_name">Enter name: </label>
    <input id="team_name" type="text" name="name_field" value="Default name for team.">
    <input type="submit" value="OK">
# </form>
1. the view gets a request, 
2. performs any actions required including reading data from the models,
3. then generates and returns an HTML page 
