# Video_Hosting

CREATE DATABASE video_db;

CREATE USER video_user WITH PASSWORD '4276';

ALTER ROLE video_user SET client_encoding TO 'utf8';

ALTER ROLE video_user SET default_transaction_isolation TO 'read committed';

ALTER ROLE video_user SET timezone TO 'UTC';

GRANT ALL PRIVILEGES ON DATABASE video_db TO video_user;