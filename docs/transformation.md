# Transformation model

The pipeline reads a declared source schema, maps source names to destination fields, normalizes text and contact values, splits composite names when required, validates required columns, and writes a deterministic output file.

Rejected records are isolated from successful output so one malformed row does not silently corrupt the full delivery.
