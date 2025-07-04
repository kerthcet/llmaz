---
title: llmaz
---

{{< blocks/cover color="primary" image_anchor="top" height="max" >}}
<p><img class="w-50 h-auto mb-4" src="/images/logo-white.png" class="llmaz-logo" /></p>
<a class="btn btn-lg btn-secondary me-3 mb-4" href="/docs/">
  Learn More <i class="fas fa-arrow-alt-circle-right ms-2"></i>
</a>
<a class="btn btn-lg btn-secondary me-3 mb-4" href="https://github.com/InftyAI/llmaz">
  GitHub <i class="fab fa-github ms-2 "></i>
</a>
<p class="lead mt-5 -text-white">Easy, advanced inference platform for large language models on Kubernetes.</p>
{{< blocks/link-down color="white" >}}

{{< /blocks/cover >}}


{{% blocks/section color="white" type="row" %}}

<p class="h1 text-center mb-4">Key Features</p>

{{% blocks/feature icon="fas fa-user-shield" title="Easy of Use" %}}
People can quick deploy a LLM service with minimal configurations.
{{% /blocks/feature %}}

{{% blocks/feature icon="fas fa-cubes" title="Broad Backends Support" %}}
llmaz supports a wide range of advanced inference backends for different scenarios, like <a href="https://github.com/vllm-project/vllm">vLLM</a>, <a href="https://github.com/huggingface/text-generation-inference">Text-Generation-Inference</a>, <a href="https://github.com/sgl-project/sglang">SGLang</a>, <a href="https://github.com/ggerganov/llama.cpp">llama.cpp</a>. Find the full list of supported backends <a href="/InftyAI/llmaz/blob/main/docs/support-backends.md">here</a>.
{{% /blocks/feature %}}

{{% blocks/feature icon="fas fa-random" title="Heterogeneous Cluster Support" %}}
llmaz supports serving the same LLM with various accelerators to optimize cost and performance.
{{% /blocks/feature %}}

{{% blocks/feature icon="fas fa-list-alt" title="Various Model Providers" %}}
llmaz supports a wide range of model providers, such as <a href="https://huggingface.co/" rel="nofollow">HuggingFace</a>, <a href="https://www.modelscope.cn" rel="nofollow">ModelScope</a>, ObjectStores. llmaz will automatically handle the model loading, requiring no effort from users.
{{% /blocks/feature %}}

{{% blocks/feature icon="fas fa-sitemap" title="Distributed Serving" %}}
Multi-host & homogeneous xPyD distributed serving support with <a href="https://github.com/kubernetes-sigs/lws">LWS</a> from day 0. Will implement the heterogeneous xPyD in the future.
{{% /blocks/feature %}}

{{% blocks/feature icon="fas fa-door-open" title="AI Gateway Support" %}}
Offering capabilities like token-based rate limiting, model routing with the integration of <a href="https://aigateway.envoyproxy.io/" rel="nofollow">Envoy AI Gateway</a>.
{{% /blocks/feature %}}

{{% blocks/feature icon="fas fa-expand-arrows-alt" title="Scaling Efficiency" %}}
Horizontal Pod scaling with <a href="/InftyAI/llmaz/blob/main/docs/examples/hpa/README.md">HPA</a> based on LLM-focused metrics and node(spot instance) autoscaling with <a href="https://github.com/kubernetes-sigs/karpenter">Karpenter</a>.
{{% /blocks/feature %}}

{{% blocks/feature icon="fas fa-comments" title="Build-in ChatUI" %}}
Out-of-the-box chatbot support with the integration of <a href="https://github.com/open-webui/open-webui">Open WebUI</a>, offering capacities like function call, RAG, web search and more, see configurations <a href="/InftyAI/llmaz/blob/main/docs/open-webui.md">here</a>.
{{% /blocks/feature %}}

{{% blocks/feature icon="fas fa-ellipsis-h" title="More in the future" %}}
{{% /blocks/feature %}}

{{% /blocks/section %}}
