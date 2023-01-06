# blog-rails-next
Blog using rails and next for promote rest-api-generator gem.

## Back-end

## Rails

- ### rest-api-generator (Build api faster)
  - Specs: [rspec](https://github.com/rspec/rspec-rails)
  - Factories: [factory_bot](https://github.com/thoughtbot/factory_bot)
  - For docs: [rswag](https://github.com/rswag/rswag) (`SWAGGER_DRY_RUN=0 rails rswag`)
  

`rails g rest_api_generator:resource Post title:string author:string content:rich_text --spec=rswag`

- ### Avo (Admin)
  - Change api_only=false
  - Install propshaft

- ### Others
  - Serializer: AMS 
  - Text editor: Action Text with Trix
  - Images: Action Storage

## Front-end

- ### Next.js
  - Template: `npx create-next-app --example blog-starter blog-starter-app`
  - Link: https://next-blog-starter.vercel.app/
