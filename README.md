# iPXE Builder Template Repo

這是給使用者 fork 的模板 repo。

用途：
- 接收 Worker 觸發的 `workflow_dispatch`
- 在使用者自己的 fork repo 內編譯 `ipxe.efi`
- 產生 artifact（`ipxe-efi`）供下載

## 必要檔案

- `.github/workflows/build-ipxe-efi.yml`

## 注意

- 此 repo 不需要 Cloudflare Worker 程式碼。
- 使用者 fork 後，編譯成本與產物都在使用者自己的 repo。
