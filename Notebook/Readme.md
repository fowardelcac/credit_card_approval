https://www.kaggle.com/datasets/alexisbcook/synthetic-credit-card-approval

The dataset contains, for each applicant:

income (in the Income column),
the number of children (in the Num_Children column),
whether the applicant owns a car (in the Own_Car column, the value is 1 if the applicant owns a car, and is else 0), and
whether the applicant owns a home (in the Own_Housing column, the value is 1 if the applicant owns a home, and is else 0)
When evaluating fairness, we'll check how the model performs for users in different groups, as identified by the Group column:

The Group column breaks the users into two groups (where each group corresponds to either 0 or 1).
For instance, you can think of the column as breaking the users into two different races, ethnicities, or gender groupings. If the column breaks users into different ethnicities, 0 could correspond to a non-Hispanic user, while 1 corresponds to a Hispanic user.
