<style>
.box {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 15px;
    background-color: #D3D3D3;
    border-radius: 10px;
}

.box select {
    background-color: #595959;
}
</style>

<center>
@lab.title
</center>

<br>

<div class="box">
    <b>Select Lab:</b>&nbsp;&nbsp;&nbsp;&nbsp;
    @lab.DropDownList(module)[Intro, Outro, Scripts, Lab 0, Lab 1, Lab 2, Lab 3, Lab 4, Lab 5, Lab 6, Lab 7, Lab 8, Lab 9, Lab 10, Lab 11, Lab 12, Lab 13, Lab 14, Lab 15]
</div>
---


:::module(module=Intro)

## Scenario

[Provide a brief scenario describing the purpose of the lab and the business or technical context.]

<div class="mission-box">

<h2>🎯 YOUR MISSION</h2>

<ol>
<li>[Mission Task 1]</li>
<li>[Mission Task 2]</li>
<li>[Mission Task 3]</li>
<li>[Mission Task 4]</li>
<li>[Mission Task 5]</li>
<li>[Mission Task 6]</li>
</ol>

### Exam Objectives

This activity is designed to test your understanding of and ability to apply concepts from the following CompTIA objective(s):

- 1.1

### Lab Environment

Describe the systems, tools, and resources available to complete this activity.

Example:

- **Endpoint:** WIN-PC1
- **Server:** SRV-OT1
- **SIEM:** Wazuh
- **PLC:** OpenPLC
- **HMI:** Node-RED
- **Utilities:** Wireshark, Sysmon

</div>

:::


:::module(module=Scripts)

# Scripts

## Enable Hints

@lab.DropDownList(ShowHints)[Yes,No]

:::hint-toggle

<span class="label slider-heading">Hints Enabled</span>

<span class="label">No</span>

<label class="switch">
    <input type="checkbox"
           class="checkMode"
           title="Toggle Hints"
           checked>
    <span class="slider round"></span>
</label>

<span class="label">Yes</span>



## Sample Hint

<details>
  <summary><b>💡 Hint</b> - Click here if you need assistance.</summary>

  <br>

  <code>su - student1</code>

</details>

## Sample Investigation Tip

<details>
  <summary><b>🔍 Investigation Tip</b></summary>

  Review the authentication logs for any failed login attempts before proceeding.

</details>

##AI
<iframe
  src="https://ai-server:3001/embed/chat?embedId=bf6e4b29-b4e4-451a-aefb-4c90bfb6f578"
  width="100%"
  height="650"
  frameborder="0"
  allow="microphone">
	<script>
    data-embed-id="bf6e4b29-b4e4-451a-aefb-4c90bfb6f578"
    data-base-api-url="https://ai-server:3001/api/embed"
    src="https://ai-server:3001/embed/anythingllm-chat-widget.min.js"> 
    data-assistant-name="${EMBED_ASSISTANT_NAME}"
    data-greeting="${EMBED_GREETING}"
    data-default-messages="${EMBED_SUGGESTIONS}"
    data-button-color="${EMBED_BUTTON_COLOR}"
    data-assistant-bg-color="#f0f4f8"
    data-user-bg-color="${EMBED_BUTTON_COLOR}"
    data-chat-icon="${EMBED_ICON}"
    data-position="bottom-right"
    data-window-height="550px"
    data-window-width="380px"
    data-text-size="14"
    data-open-on-load="on"
	</script>
</iframe>

:::


:::module(module=Lab 0)

:::

:::module(module=Lab 1)

:::

:::module(module=Lab 2)

:::

:::module(module=Lab 3)

:::

:::module(module=Lab 4)

:::

:::module(module=Lab 5)

:::

:::module(module=Lab 6)

:::

:::module(module=Lab 7)

:::

:::module(module=Lab 8)

:::

:::module(module=Lab 9)

:::

:::module(module=Lab 10)

:::

:::module(module=Lab 11)

:::

:::module(module=Lab 12)

:::

:::module(module=Lab 13)

:::

:::module(module=Lab 14)

:::

:::module(module=Lab 15)

:::

:::module(module=Outro)

## Grade Lab

>You have completed the following tasks:

- [Task 1]
- [Task 2]
- [Task 3]

That concludes this lab. To submit this lab for grading:

1. Select check boxes to mark all tasks complete.
2. Submit responses to all questions and activities.

>[!alert] Select:
>
>- **Submit** in the bottom-right corner, then **Yes** to submit your lab for grading. You may relaunch the lab and attempt it again at any time.
>- **Save & Exit** in the top-right corner to save your progress and return later. Your progress will be retained for seven (7) days.

:::
