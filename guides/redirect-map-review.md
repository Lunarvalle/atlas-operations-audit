# Review a redirect map before migration

A static map can contain a loop: /old-a -> /old-b and /old-b -> /old-a. A chain is different: /old-a -> /step-b -> /new-c. A loop needs correction; an intermediate hop needs review of whether it is intentional.

[Redirect Guard](../products/redirect-guard.md) reviews supplied mappings. Inspect its [synthetic input and expected output](../examples/redirect-guard.json), preserve the original export and review flagged paths with the migration owner. It does not make HTTP requests or prove a real destination currently returns 200. A clean static map is not proof that a live migration succeeded.

Use an appropriate live-site check after the map review. No SEO ranking gain or fabricated improvement percentage is claimed. All five language options belong to one product.
