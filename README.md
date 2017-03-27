# React Router Lab API

## Install

```bash
git clone git@github.com:ga-wdi-exercises/react-router-lab-api.git
cd react-router-lab-api
rails db:create db:migrate db:seed
rails s
```

## Schema

```rb
ActiveRecord::Schema.define(version: 20170326150322) do
  enable_extension "plpgsql"
  create_table "stocks", force: :cascade do |t|
    t.string   "name"
    t.string   "symbol"
    t.datetime "created_at", null: false
    t.datetime "updated_at", null: false
  end
end
```
