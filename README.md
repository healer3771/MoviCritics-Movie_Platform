# MoviCritics-Movie_Platform

• Engineered a robust movie recommendation platform called MoviCritics, leveraging a microservices-inspired architecture. The system
utilized PHP, HTML, CSS, SQL, React.js, and RabbitMQ to provide seamless user interactions, real-time data processing, and dynamic
external API integrations

• Implemented a secure DMZ layer to integrate with an open-source movie API for fetching additional movie data, including new
releases and personalized recommendations. This design reduced database load and improved data accuracy for titles, descriptions,
and user ratings

• Delivered advanced user features, including secure login, session validation, password hashing, personalized watchlists, movie ratings,
and real-time comment functionality. The system also introduced daily notifications for users about new movie releases relevant to
their watchlists

• Designed error-handling and caching mechanisms to address API response inconsistencies, such as missing fields or delayed data.
Enhanced performance by reducing redundant API calls through database caching techniques

• Enhanced the backend with RabbitMQ message queues, enabling smooth communication between the front-end, database, and
external API services. Developed dedicated queues for efficient movie data retrieval, recommendation handling, and user interactions
