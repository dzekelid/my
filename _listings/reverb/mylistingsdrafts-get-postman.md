{
  "info": {
    "name": "reverb Get My Listings Drafts",
    "_postman_id": "a5091a50-3232-4a48-8929-e9b935634427",
    "description": "Retrieve a list your draft listings",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "fb571ea6-bcee-4506-9e7f-eded97b3bcdd",
          "name": "getMyListingsDrafts",
          "request": {
            "url": "http://api.reverb.com/api/my/listings/drafts?accepts_gift_cards=%7B%7D&accepts_payment_plans=%7B%7D&auction_price_max=%7B%7D&category=%7B%7D&conditions=%7B%7D&currency=%7B%7D&decade=%7B%7D&exclude_auctions=%7B%7D&finish=%7B%7D&handmade=%7B%7D&item_city=%7B%7D&item_country=%7B%7D&item_region=%7B%7D&item_state=%7B%7D&listing_type=%7B%7D&make=%7B%7D&model=%7B%7D&must_not=%7B%7D&not_ids=%7B%7D&preferred_seller=%7B%7D&price_max=%7B%7D&price_min=%7B%7D&product_type=%7B%7D&query=%7B%7D&ships_to=%7B%7D&shop=%7B%7D&shop_id=%7B%7D&watchers_count_min=%7B%7D&year_max=%7B%7D&year_min=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a list your draft listings"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49198300-f807-4420-94f2-67629f9f92b3"
            }
          ]
        }
      ]
    }
  ]
}