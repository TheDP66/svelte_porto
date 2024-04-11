<script>
  import Watermark from "./Watermark.svelte";
  import { Layout } from "antd";

  const siderStyle = {
    textAlign: "center",
    lineHeight: "120px",
    color: "#fff",
    backgroundColor: "#3ba0e9",
  };
</script>

<div class="flex flex-row">
  <Watermark />
  <Layout.Sider style={siderStyle}>
    <div class="container">
      <section>1</section>
      <section>2</section>
      <section>3</section>
    </div>
  </Layout.Sider>
</div>
