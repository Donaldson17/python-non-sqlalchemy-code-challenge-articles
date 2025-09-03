# TODO: Implement Required Methods and Functionalities

## Article Class
- [x] `__init__` method with validations for title, author, and magazine.
- [x] `title` property with restrictions on modification.
- [ ] Add `author` property with a setter.
- [ ] Add `magazine` property with a setter.

## Author Class
- [x] `__init__` method with validations for name.
- [x] `name` property with restrictions on modification.
- [x] `articles()` method to return a list of articles.
- [x] `magazines()` method to return a unique list of magazines.
- [x] `add_article()` method to create and return a new Article instance.
- [x] `topic_areas()` method to return a unique list of categories.

## Magazine Class
- [x] `__init__` method with validations for name and category.
- [x] `name` property with a setter.
- [x] `category` property with a setter.
- [x] `articles()` method to return a list of articles.
- [x] `contributors()` method to return a unique list of authors.
- [x] `article_titles()` method to return a list of article titles.
- [x] `contributing_authors()` method to return authors with more than 2 articles.
- [x] `top_publisher()` class method to return the Magazine instance with the most articles.

## Testing
- [ ] Run `pytest` to ensure all tests are working.
