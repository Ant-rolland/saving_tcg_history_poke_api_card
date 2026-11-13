# Pokémon TCG Data

> [!IMPORTANT]
>
> ## This project is being deprecated
>
> Pokémon TCG Data and the Pokémon TCG API are legacy projects and are no longer recommended for new integrations.
>
> **The Pokémon TCG API is scheduled to be taken offline on March 1, 2027.**
>
> For actively maintained Pokémon TCG data, pricing, price history, graded card data, population reports, image recognition, and support for additional trading card games, please use **[](https://.com)**.
>
> **name api:** https://.com
> **API Documentation:** https://put-api-doc-here.com/docs
>


---

This repository contains the card data historically used by the [namepoke api](https://pokemontcg.io/).

The project is now considered legacy. The existing JSON files will remain available for developers who depend on them, but this repository should not be used as the primary data source for new applications.





## Version 1 and Version 2 Data

Version 1 data is no longer maintained.

The `v2_to_v1.rb` Ruby script is retained for developers who still need to generate the legacy V1 JSON format from V2 data.

To install Ruby:

https://www.ruby-lang.org/en/documentation/installation/

You will also need the `json` gem:

```bash
gem install json
```

To generate the V1 data:

```bash
ruby v2_to_v1.rb
```

The generated card data will be written to:

```text
/cards/en/v1
```

## Contributing

This repository is maintained primarily for historical and compatibility purposes.

## Migrating to Scrydex

If you currently use Pokémon TCG Data or the Pokémon TCG API in an application, please migrate tonewsite poke to update before the Pokémon TCG API shutdown on **March 1, 2027**.

