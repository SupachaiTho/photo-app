# Photo Application

This is a Photo Stored and Management application made with Ruby on Rails during The Complete Ruby on Rails Developer Course

# Functionalities

- Sign Up
  - Comfirmation via email
  - Payment with Stripe, https://stripe.com/docs/testing.
- Log In
- Log Out
- Edit profile
- New
  - Upload Iamge to S3 Bucket
- Edit
- Delete

# Model Associations

```
User **many_to_many** Image
User **one_to_one** Payment
```

# Technologies

- Ruby 2.3.0
- Rails 4.2.5
- gem devise
- gem twitter-bootstrap-rails
- gem devise-bootstrap-views
- gem stripe
- gem carrierwave
- gem mini_magick
- gem fog

# Demo

Running demo at: https://photo-app-supachai.herokuapp.com
