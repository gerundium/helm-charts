# helm-charts
Gerundium Public Helm charts

<p style="text-align: center;">Welcome friend!</br><svg xmlns="http://www.w3.org/2000/svg" height="1em" fill="currentColor" viewBox="0 0 512 448">
  <path d="M 272 64 L 272 64 L 376 64 Q 408 64 434 48 Q 460 32 475 5 Q 478 0 483 0 Q 489 0 491 5 Q 512 60 512 125 Q 511 206 479 271 Q 448 337 394 376 Q 340 415 273 416 L 272 416 Q 210 415 164 379 Q 118 343 102 285 Q 50 333 48 408 L 48 424 Q 46 446 24 448 Q 2 446 0 424 L 0 408 Q 1 351 26 304 Q 52 258 96 228 Q 103 158 152 112 Q 200 66 272 64 L 272 64 L 272 64 Z M 190 211 Q 190 233 206 249 L 277 318 Q 288 327 299 318 L 370 249 Q 386 233 386 211 Q 386 188 371 173 Q 355 158 333 157 L 331 157 Q 309 158 293 173 L 288 178 L 283 173 Q 267 158 245 157 L 243 157 Q 220 158 205 173 Q 190 188 190 211 L 190 211 Z" />
</svg></p>

## Homer

<p style="text-align: center;">
<!-- circle-info icon by Free Icons (https://free-icons.github.io/free-icons/) -->
<svg xmlns="http://www.w3.org/2000/svg" height="1em" fill="currentColor" viewBox="0 0 512 512">
  <path
    d="M 256 512 Q 326 511 384 478 L 384 478 Q 442 444 478 384 Q 512 323 512 256 Q 512 189 478 128 Q 442 68 384 34 Q 326 1 256 0 Q 186 1 128 34 Q 70 68 34 128 Q 0 189 0 256 Q 0 323 34 384 Q 70 444 128 478 Q 186 511 256 512 L 256 512 Z M 216 336 L 240 336 L 240 272 L 216 272 Q 194 270 192 248 Q 194 226 216 224 L 264 224 Q 286 226 288 248 L 288 336 L 296 336 Q 318 338 320 360 Q 318 382 296 384 L 216 384 Q 194 382 192 360 Q 194 338 216 336 L 216 336 Z M 256 128 Q 270 128 279 137 L 279 137 Q 288 146 288 160 Q 288 174 279 183 Q 270 192 256 192 Q 242 192 233 183 Q 224 174 224 160 Q 224 146 233 137 Q 242 128 256 128 L 256 128 Z"
  />
</svg>
</p>



## TL;DR;

### Add helm repository
```bash
# Add
helm repo add gerundium https://gerundium.github.io/helm-charts/

# Update helm cache
helm repo update
```

### Install a chart
```bash
helm install <MY-RELEASE-NAME> gerundium/<CHART-NAME> [--values=overrides.yaml]
```