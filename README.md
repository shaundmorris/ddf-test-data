ddf-test-data
=============

Test data that can be ingested into DDF

# Ingest instructions
1. Download DDF
2. Clone ddf-test-data repository
   ```
   git clone https://github.com/shaundmorris/ddf-test-data.git
   ```
2. Start DDF
3. Install Catalog, UI, and Solr Applications
4. On the command line use the Catalog Ingest Command:
   ```
   catalog:ingest -t geojson CLONE_DIR/ddf-test-data/json
   ```
5. 80 airport records will be ingested
