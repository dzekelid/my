---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Post My Negotiations Decline
  description: Post my negotiations decline.
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /my/account:
    get:
      summary: Get My Account
      description: Get account details
      operationId: getMyAccount
      x-api-path-slug: myaccount-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Account
    put:
      summary: Put My Account
      description: Update account details
      operationId: putMyAccount
      x-api-path-slug: myaccount-put
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - My
      - Account
  /my/addresses:
    get:
      summary: Get My Addresses
      description: See all addresses in your address book
      operationId: getMyAddresses
      x-api-path-slug: myaddresses-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
    post:
      summary: Post My Addresses
      description: Create a new address in your address book
      operationId: postMyAddresses
      x-api-path-slug: myaddresses-post
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
  /my/addresses/{address_id}:
    delete:
      summary: Delete My Addresses Address
      description: Delete an existing address in your address book
      operationId: deleteMyAddressesAddress
      x-api-path-slug: myaddressesaddress-id-delete
      parameters:
      - in: path
        name: address_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
      - Address
      - Id
    put:
      summary: Put My Addresses Address
      description: Update an existing address in your address book
      operationId: putMyAddressesAddress
      x-api-path-slug: myaddressesaddress-id-put
      parameters:
      - in: path
        name: address_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
      - Address
      - Id
  /my/conversations:
    get:
      summary: Get My Conversations
      description: Get a list of your conversations
      operationId: getMyConversations
      x-api-path-slug: myconversations-get
      parameters:
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      - in: query
        name: search
        description: Query string to search conversations by
      - in: query
        name: unread_only
        description: Show unread conversations only
      responses:
        200:
          description: OK
      tags:
      - My
      - Conversations
    post:
      summary: Post My Conversations
      description: Post my conversations.
      operationId: postMyConversations
      x-api-path-slug: myconversations-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - My
      - Conversations
  /my/conversations/{conversation_id}/messages:
    post:
      summary: Post My Conversations Conversation Messages
      description: Post my conversations conversation messages.
      operationId: postMyConversationsConversationMessages
      x-api-path-slug: myconversationsconversation-idmessages-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: conversation_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Conversations
      - Conversation
      - Id
      - Messages
  /my/conversations/{id}:
    get:
      summary: Get My Conversations
      description: Display conversation details with messages in natural time order
        (oldest to newest)
      operationId: getMyConversations
      x-api-path-slug: myconversationsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - My
      - Conversations
      - Id
    put:
      summary: Put My Conversations
      description: Mark a conversation read/unread
      operationId: putMyConversations
      x-api-path-slug: myconversationsid-put
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - My
      - Conversations
      - Id
  /my/counts:
    get:
      summary: Get My Counts
      description: Get your actionable status counts
      operationId: getMyCounts
      x-api-path-slug: mycounts-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Counts
  /my/curated_set/product/{product_id}:
    delete:
      summary: Delete My Curated Set Product Product
      description: Delete my curated set product product.
      operationId: deleteMyCuratedSetProductProduct
      x-api-path-slug: mycurated-setproductproduct-id-delete
      parameters:
      - in: path
        name: product_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Curated
      - Set
      - Product
      - Product
      - Id
    post:
      summary: Post My Curated Set Product Product
      description: Post my curated set product product.
      operationId: postMyCuratedSetProductProduct
      x-api-path-slug: mycurated-setproductproduct-id-post
      parameters:
      - in: path
        name: product_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Curated
      - Set
      - Product
      - Product
      - Id
  /my/feed:
    get:
      summary: Get My Feed
      description: Get listings from your feed
      operationId: getMyFeed
      x-api-path-slug: myfeed-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feed
  /my/feed/customize:
    get:
      summary: Get My Feed Customize
      description: get your feed customization options
      operationId: getMyFeedCustomize
      x-api-path-slug: myfeedcustomize-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feed
      - Customize
  /my/feed/grid:
    get:
      summary: Get My Feed Gr
      description: Get my feed gr.
      operationId: getMyFeedGr
      x-api-path-slug: myfeedgrid-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feed
      - Grid
  /my/feedback/received:
    get:
      summary: Get My Feedback Received
      description: List of received feedback
      operationId: getMyFeedbackReceived
      x-api-path-slug: myfeedbackreceived-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feedback
      - Received
  /my/feedback/sent:
    get:
      summary: Get My Feedback Sent
      description: List of sent feedback
      operationId: getMyFeedbackSent
      x-api-path-slug: myfeedbacksent-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feedback
      - Sent
  /my/follows:
    get:
      summary: Get My Follows
      description: See what the user is following
      operationId: getMyFollows
      x-api-path-slug: myfollows-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
  /my/follows/articles:
    get:
      summary: Get My Follows Articles
      description: Returns a user's ArticleCategoryFollows
      operationId: getMyFollowsArticles
      x-api-path-slug: myfollowsarticles-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Articles
    post:
      summary: Post My Follows Articles
      description: Set a user's ArticleCategoryFollows
      operationId: postMyFollowsArticles
      x-api-path-slug: myfollowsarticles-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Articles
  /my/follows/brands/{slug}:
    delete:
      summary: Delete My Follows Brands Slug
      description: Delete my follows brands slug.
      operationId: deleteMyFollowsBrandsSlug
      x-api-path-slug: myfollowsbrandsslug-delete
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Brands
      - Slug
    get:
      summary: Get My Follows Brands Slug
      description: Get my follows brands slug.
      operationId: getMyFollowsBrandsSlug
      x-api-path-slug: myfollowsbrandsslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Brands
      - Slug
    post:
      summary: Post My Follows Brands Slug
      description: Post my follows brands slug.
      operationId: postMyFollowsBrandsSlug
      x-api-path-slug: myfollowsbrandsslug-post
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Brands
      - Slug
  /my/follows/categories/{category}/{subcategory}:
    delete:
      summary: Delete My Follows Categories Category Subcategory
      description: Delete my follows categories category subcategory.
      operationId: deleteMyFollowsCategoriesCategorySubcategory
      x-api-path-slug: myfollowscategoriescategorysubcategory-delete
      parameters:
      - in: path
        name: category
      - in: path
        name: subcategory
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Category
      - Subcategory
    get:
      summary: Get My Follows Categories Category Subcategory
      description: Get my follows categories category subcategory.
      operationId: getMyFollowsCategoriesCategorySubcategory
      x-api-path-slug: myfollowscategoriescategorysubcategory-get
      parameters:
      - in: path
        name: category
      - in: path
        name: subcategory
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Category
      - Subcategory
    post:
      summary: Post My Follows Categories Category Subcategory
      description: Post my follows categories category subcategory.
      operationId: postMyFollowsCategoriesCategorySubcategory
      x-api-path-slug: myfollowscategoriescategorysubcategory-post
      parameters:
      - in: path
        name: category
      - in: path
        name: subcategory
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Category
      - Subcategory
  /my/follows/categories/{identifier}:
    delete:
      summary: Delete My Follows Categories Entifier
      description: Delete my follows categories entifier.
      operationId: deleteMyFollowsCategoriesEntifier
      x-api-path-slug: myfollowscategoriesidentifier-delete
      parameters:
      - in: path
        name: identifier
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Identifier
    get:
      summary: Get My Follows Categories Entifier
      description: Get my follows categories entifier.
      operationId: getMyFollowsCategoriesEntifier
      x-api-path-slug: myfollowscategoriesidentifier-get
      parameters:
      - in: path
        name: identifier
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Identifier
    post:
      summary: Post My Follows Categories Entifier
      description: Post my follows categories entifier.
      operationId: postMyFollowsCategoriesEntifier
      x-api-path-slug: myfollowscategoriesidentifier-post
      parameters:
      - in: path
        name: identifier
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Identifier
  /my/follows/collections/{slug}:
    delete:
      summary: Delete My Follows Collections Slug
      description: Delete my follows collections slug.
      operationId: deleteMyFollowsCollectionsSlug
      x-api-path-slug: myfollowscollectionsslug-delete
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Collections
      - Slug
    get:
      summary: Get My Follows Collections Slug
      description: Get my follows collections slug.
      operationId: getMyFollowsCollectionsSlug
      x-api-path-slug: myfollowscollectionsslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Collections
      - Slug
    post:
      summary: Post My Follows Collections Slug
      description: Post my follows collections slug.
      operationId: postMyFollowsCollectionsSlug
      x-api-path-slug: myfollowscollectionsslug-post
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Collections
      - Slug
  /my/follows/handpicked/{slug}:
    delete:
      summary: Delete My Follows Handpicked Slug
      description: Delete my follows handpicked slug.
      operationId: deleteMyFollowsHandpickedSlug
      x-api-path-slug: myfollowshandpickedslug-delete
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Handpicked
      - Slug
    get:
      summary: Get My Follows Handpicked Slug
      description: Follow status for a handpicked collection
      operationId: getMyFollowsHandpickedSlug
      x-api-path-slug: myfollowshandpickedslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Handpicked
      - Slug
    post:
      summary: Post My Follows Handpicked Slug
      description: Post my follows handpicked slug.
      operationId: postMyFollowsHandpickedSlug
      x-api-path-slug: myfollowshandpickedslug-post
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Handpicked
      - Slug
  /my/follows/search:
    get:
      summary: Get My Follows Search
      description: Follow status for a search
      operationId: getMyFollowsSearch
      x-api-path-slug: myfollowssearch-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Search
    post:
      summary: Post My Follows Search
      description: Post my follows search.
      operationId: postMyFollowsSearch
      x-api-path-slug: myfollowssearch-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Search
  /my/follows/shops/{slug}:
    delete:
      summary: Delete My Follows Shops Slug
      description: Delete my follows shops slug.
      operationId: deleteMyFollowsShopsSlug
      x-api-path-slug: myfollowsshopsslug-delete
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Shops
      - Slug
    get:
      summary: Get My Follows Shops Slug
      description: Get my follows shops slug.
      operationId: getMyFollowsShopsSlug
      x-api-path-slug: myfollowsshopsslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Shops
      - Slug
    post:
      summary: Post My Follows Shops Slug
      description: Post my follows shops slug.
      operationId: postMyFollowsShopsSlug
      x-api-path-slug: myfollowsshopsslug-post
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Shops
      - Slug
  /my/follows/{follow_id}:
    delete:
      summary: Delete My Follows Follow
      description: Delete my follows follow.
      operationId: deleteMyFollowsFollow
      x-api-path-slug: myfollowsfollow-id-delete
      parameters:
      - in: path
        name: follow_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Follow
      - Id
  /my/follows/{follow_id}/alert:
    delete:
      summary: Delete My Follows Follow Alert
      description: Delete my follows follow alert.
      operationId: deleteMyFollowsFollowAlert
      x-api-path-slug: myfollowsfollow-idalert-delete
      parameters:
      - in: path
        name: follow_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Follow
      - Id
      - Alert
    post:
      summary: Post My Follows Follow Alert
      description: Post my follows follow alert.
      operationId: postMyFollowsFollowAlert
      x-api-path-slug: myfollowsfollow-idalert-post
      parameters:
      - in: path
        name: follow_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Follow
      - Id
      - Alert
  /my/listings:
    get:
      summary: Get My Listings
      description: Retrieve a list of live listings for the seller. To search all
        listings specify state=all
      operationId: getMyListings
      x-api-path-slug: mylistings-get
      parameters:
      - in: query
        name: accepts_gift_cards
        description: If true, include only items that accept gift cards
      - in: query
        name: accepts_payment_plans
        description: If true, only show items that can be purchased with a payment
          plan
      - in: query
        name: auction_price_max
        description: Maximum current auction price
      - in: query
        name: category
        description: Category slug from /api/categories
      - in: query
        name: conditions
        description: 'Condition: all,new,b-stock,used,non-functioning'
      - in: query
        name: currency
        description: The currency to be used for the price filters
      - in: query
        name: decade
        description: 'Decade: e'
      - in: query
        name: exclude_auctions
        description: If true, exclude auctions
      - in: query
        name: finish
        description: Visual finish of the item, common for guitars
      - in: query
        name: handmade
        description: Handmade items only
      - in: query
        name: item_city
        description: City where item is located
      - in: query
        name: item_country
        description: DEPRECATED - Country code where item is located
      - in: query
        name: item_region
        description: Country code where item is located
      - in: query
        name: item_state
        description: State or region code where item is located
      - in: query
        name: listing_type
        description: 'Type of listing: auctions,offers'
      - in: query
        name: make
        description: Make(s)/brand of item (e
      - in: query
        name: model
        description: Model of item (e
      - in: query
        name: must_not
        description: Search term negation
      - in: query
        name: not_ids
        description: Listing ID negation
      - in: query
        name: preferred_seller
        description: If true, include only items by Reverb Preferred Sellers
      - in: query
        name: price_max
        description: Maximum price of search results (USD)
      - in: query
        name: price_min
        description: Minimum price of search results (USD)
      - in: query
        name: product_type
        description: Product type slug from /api/categories
      - in: query
        name: query
        description: Search query
      - in: query
        name: ships_to
        description: Limit search to items that ship to this country code
      - in: query
        name: shop
        description: Slug of shop to search
      - in: query
        name: shop_id
        description: ID of shop to search
      - in: query
        name: sku
        description: Find a listing by sku
      - in: query
        name: state
        description: 'Available: [all, draft, ended, live, ordered, sold_out, suspended,
          seller_unavailable]'
      - in: query
        name: watchers_count_min
        description: Minimum number of watchers (used to find popular items)
      - in: query
        name: year_max
        description: Maximum year of manufacture
      - in: query
        name: year_min
        description: Minumum year of manufacture
      responses:
        200:
          description: OK
      tags:
      - My
      - Listings
  /my/listings/drafts:
    get:
      summary: Get My Listings Drafts
      description: Retrieve a list your draft listings
      operationId: getMyListingsDrafts
      x-api-path-slug: mylistingsdrafts-get
      parameters:
      - in: query
        name: accepts_gift_cards
        description: If true, include only items that accept gift cards
      - in: query
        name: accepts_payment_plans
        description: If true, only show items that can be purchased with a payment
          plan
      - in: query
        name: auction_price_max
        description: Maximum current auction price
      - in: query
        name: category
        description: Category slug from /api/categories
      - in: query
        name: conditions
        description: 'Condition: all,new,b-stock,used,non-functioning'
      - in: query
        name: currency
        description: The currency to be used for the price filters
      - in: query
        name: decade
        description: 'Decade: e'
      - in: query
        name: exclude_auctions
        description: If true, exclude auctions
      - in: query
        name: finish
        description: Visual finish of the item, common for guitars
      - in: query
        name: handmade
        description: Handmade items only
      - in: query
        name: item_city
        description: City where item is located
      - in: query
        name: item_country
        description: DEPRECATED - Country code where item is located
      - in: query
        name: item_region
        description: Country code where item is located
      - in: query
        name: item_state
        description: State or region code where item is located
      - in: query
        name: listing_type
        description: 'Type of listing: auctions,offers'
      - in: query
        name: make
        description: Make(s)/brand of item (e
      - in: query
        name: model
        description: Model of item (e
      - in: query
        name: must_not
        description: Search term negation
      - in: query
        name: not_ids
        description: Listing ID negation
      - in: query
        name: preferred_seller
        description: If true, include only items by Reverb Preferred Sellers
      - in: query
        name: price_max
        description: Maximum price of search results (USD)
      - in: query
        name: price_min
        description: Minimum price of search results (USD)
      - in: query
        name: product_type
        description: Product type slug from /api/categories
      - in: query
        name: query
        description: Search query
      - in: query
        name: ships_to
        description: Limit search to items that ship to this country code
      - in: query
        name: shop
        description: Slug of shop to search
      - in: query
        name: shop_id
        description: ID of shop to search
      - in: query
        name: watchers_count_min
        description: Minimum number of watchers (used to find popular items)
      - in: query
        name: year_max
        description: Maximum year of manufacture
      - in: query
        name: year_min
        description: Minumum year of manufacture
      responses:
        200:
          description: OK
      tags:
      - My
      - Listings
      - Drafts
  /my/listings/negotiations:
    get:
      summary: Get My Listings Negotiations
      description: Get a list of active negotiations as a seller
      operationId: getMyListingsNegotiations
      x-api-path-slug: mylistingsnegotiations-get
      parameters:
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      responses:
        200:
          description: OK
      tags:
      - My
      - Listings
      - Negotiations
  /my/listings/{slug}/state/end:
    put:
      summary: Put My Listings Slug State End
      description: Put my listings slug state end.
      operationId: putMyListingsSlugStateEnd
      x-api-path-slug: mylistingsslugstateend-put
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Listings
      - Slug
      - State
      - End
  /my/lists:
    get:
      summary: Get My Lists
      description: Get a list of your lists (wishlist, watch list, etc)
      operationId: getMyLists
      x-api-path-slug: mylists-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Lists
  /my/negotiations/buying:
    get:
      summary: Get My Negotiations Buying
      description: Get a list of active negotiations as a buyer
      operationId: getMyNegotiationsBuying
      x-api-path-slug: mynegotiationsbuying-get
      parameters:
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      responses:
        200:
          description: OK
      tags:
      - My
      - Negotiations
      - Buying
  /my/negotiations/{id}:
    get:
      summary: Get My Negotiations
      description: Get my negotiations.
      operationId: getMyNegotiations
      x-api-path-slug: mynegotiationsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - My
      - Negotiations
      - Id
  /my/negotiations/{id}/accept:
    post:
      summary: Post My Negotiations Accept
      description: Post my negotiations accept.
      operationId: postMyNegotiationsAccept
      x-api-path-slug: mynegotiationsidaccept-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - My
      - Negotiations
      - Id
      - Accept
  /my/negotiations/{id}/counter:
    post:
      summary: Post My Negotiations Counter
      description: Post my negotiations counter.
      operationId: postMyNegotiationsCounter
      x-api-path-slug: mynegotiationsidcounter-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - My
      - Negotiations
      - Id
      - Counter
  /my/negotiations/{id}/decline:
    post:
      summary: Post My Negotiations Decline
      description: Post my negotiations decline.
      operationId: postMyNegotiationsDecline
      x-api-path-slug: mynegotiationsiddecline-post
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - My
      - Negotiations
      - Id
      - Decline
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---