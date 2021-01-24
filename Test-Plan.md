# Testing Plan
asdf

## Test Case Descriptions
All tests will be number with the following characteristics:
1. test case identifier (a number or unique name)
2. purpose of test
3. description of test
4. inputs used for test
5. expected outputs/results
6. normal/abnormal/boundary case indication
7. blackbox/whitebox test indication
8. functional/performance test indication
9. unit/integration test indication

### Login Test Pass
1. Login Pass Test
2. To test if login functionality works when inputs are correct
3. The test will go through the front end and backend components to verify user is a registered user and correctly 
inputs login details and not login without correct credentials
4. (Login Button) Correct Username, Password
5. Go to homepage
6. No action or incorrect page
7. Black box
8. Functional
9. Integration

### Login Fail Test
1. Login Fail Test
2. To test if login functionality works when inputs are incorrect
3. The test will go through the front end and backend components to verify user is a registered user and correctly 
inputs login details and not login without correct credentials
4. (Login Button) Incorrect Username, Password
5. View incorrect password text
6. No action or incorrect page or no text viewed
7. Black box
8. Functional
9. Integration

### Signup Test
1. Signup Test
2. To test if signup functionality works
3. The test will go through the front end and backend components to verify the registration process works for all fields
and stores proper information
4. (Signup Button) Name, other personal information
5. Prompt successful sign up message
6. No action, does not sign up correctly or does not store correct information
7. Black box
8. Functional
9. Integration

### Forum Post Addition Test
1. Forum Post Addition Test
2. To test if forum post is properly created
3. The test will check if the forum post box is properly viewed on the page and stored in the database
4. (Add post Button) Post title, Post content
5. Show post on homepage or forum page
6. No action, does not show correctly or does not store correct data
7. Black box
8. Functional
9. Integration

### Forum Post Delete Test
1. Forum Post Deletion Test
2. To test if forum post is properly deleted
3. The test will check if the forum post box is properly removed from the page and removed from the database
4. (Delete post Button)
5. Remove post from homepage or forum page
6. No action, does not delete correctly or does not correctly remove data
7. Black box
8. Functional
9. Integration

### Forum Post List Test
1. Forum Post List Test
2. To test if forum posts are properly viewed on a list
3. The test will check to see if the page properly loads the posts from the database and views them on the page
4. None
5. List correctly displayed from database
6. No list displayed or not properly displayed
7. White box
8. Functional
9. Unit