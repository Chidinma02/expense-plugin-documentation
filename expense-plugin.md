# expense-plugin-documentation
# Zuri Chat Expense Plugin


[![(https://lucid.app/lucidchart/invitations/accept/inv_da6ceae5-e62f-42bc-a9f8-cc0a4a002a85?viewport_loc=287%2C311%2C1480%2C616%2C0_0)]



The Zuri expense plugin hosted [here] (http://expenses.zuri.chat/)is a plugin that allows users to create and publish expense list which can be viewed by everyone in the organisation.
###### User story:The expense plugin is focused on allowing users in a firm create an expense list and submit for approval by the admin.


## Resources

-  [This] (https://www.figma.com/file/mizfCMNkiGxwfRgMkRJech/Zuri-Expenses?node-id=59%3A714) is the link to the Design file
- our repo the [zc_plugin_expenses repo] (https://github.com/zurichat/zc_plugin_expenses.git)
- the [live server](http://expenses.zuri.chat/)

### Workflow
#### user
 - on the expense channel,click on Add New List
 - Add the item name,pricing and quantity
 - Add the title and description of the item
 - A modal will then pop up to indicate that the approval will be sent to your mail.
 - At this point the list of item is not yet approved,it’s pending,till approved by the Admin.
#### Admin
- Admin accesses the list made by the user.
- Checks for name,description and price
- The admin then,approve or declines.



## Instructions

### Instruction for backend endpoints creators
1. Please take note that all plugins should follow the route <pluginurl>/api/v1/<endpoint>
2. After writing an api document it properly and make it available on <pluginurl>/docs/v1
3. For each of the api created, create a test that will call it and validate that it is working. The test has to be online and hosted via <pluginurl>/test/<endpoint>. Each test is a different task.

### Setting up your environment
1. make a fork of the [zc_plugin_expenses repo](https://github.com/zurichat/zc_plugin_expenses.git)
2. clone the forked repo to your system
3. add a remote url pointing at the [zc_plugin_expenses repo](https://github.com/zurichat/zc_plugin_expenses.git) for fetches

### Submitting a task
1. after working on a task before committing, fetch from the [zc_plugin_expenses repo](https://github.com/zurichat/zc_plugin_expenses.git) to make sure your work is synced with others
2. after commiting make a pull request 
3. in the title field write the team name i.e Team Grange, a very very brief descripton of the work done and also the number of the issues you worked on 
4. make the pull request to the [zc_plugin_expenses](https://github.com/zurichat/zc_plugin_expenses.git) repo
5. locate the issue you worked on and on the descrition field write the team name i.e Team Grange, a very very brief descripton of the work done
6. also on the description field add a link to your work on the [live server](http://expenses.zuri.chat/) for developers and a [link to your design file](https://www.figma.com/file/mizfCMNkiGxwfRgMkRJech/Zuri-Expenses?node-id=59%3A714) for designers
7. add a link to your pull request
8. and finally include a snapshot of your work on the [live server](http://expenses.zuri.chat/) or [design file](https://www.figma.com/file/mizfCMNkiGxwfRgMkRJech/Zuri-Expenses?node-id=59%3A714)


## Coding Guidelines
1. create new files only when necessary
2. try to make all work look excactly like the [designs](https://www.figma.com/file/mizfCMNkiGxwfRgMkRJech/Zuri-Expenses?node-id=59%3A714)
3. before writing any code on any file write a comment including your slack username and task issue number with start 
4. then your code 
5. and a comment including your slack username and task issue number withend keywords 
eg


```sh
Route::middleware('auth:api')->get('/user', function (Request $request) {
    return $request->user();
});

```
Collaborators:

Designer: @Gbem_ee
Frontend:@samurai
Backend:Tshux
Documentation:Artisan

Team lead:@Kelanialiyu
Executive in charge of plugins:@Abibola













