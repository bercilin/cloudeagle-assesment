package com.interview.programs;

import java.net.http.*;
import java.net.URI;

public class DropboxApiDemo {
	public static void main(String[] args) throws Exception {
		HttpClient client = HttpClient.newHttpClient();
		String accessToken = "sl.u.AF_awTuHAG7LFgtqlQVjY1a9-ifxaedudd5HuW-OYRjmKZBuWHj9YUXWQN7AtN3IKvTTayKK423b4DxN3colB0cayb3faRNmJXPXQ-5iWGcW7rehNUH-6GzuXIeRe9_00FJ1lV7_OW9xhUNONQsqCfEgR0OhKRtuo0hxZRBPjFFn5MJlIBHS0l8oneP6JcmSIaHhU6EDy9Nt2lRwrl8JdiHcqT_anucH8pUfI4PXwTSUMhFEACO3HojOH1seqaCs9LReESuRRFG_wpw-TZStKLyG08LTcJo4oQtib70kFBLwYYgw8SXxJxvU9mQz0MUneui-EmOZRJxBiA_PQYvqIQoCaBb6T-DVZ50uCxLQ0xseX7x6f9E1kEQWGSoh6wIm_DWoHMdXIbu0-wnLAeetdLSu0ksi2WTDxrrDkRpZ4Qu71PLQV06rqZpj4WWeBpe0ddQf-xIik8Ce1cPYKwSoErKwPALjPmmN-U58tHK5CIJfVOIUPb65nUiK8UKvWIUxfGg_ihGrJuu1kAkjO3lwKZ9-MTgi2R1zWbbnt8fJ8N8vyVYjbFJNadBdV8qRnkoHSgkAP8ZEyWDyUosMvcZj-218I2u01hJSnKdr2ix1WGrRQNiwO6XWmrFrWX8ZHx3FN34DE21YuN3gofrQzPpk6rW1QbtU_D66JwSSFrETKNiHsdY9zaiSD5iJE6x1Btb_v_tIQ4Wg20s5fkFP_mE4z6Yj-6Cn8DYUde2OSo-pj2RYex6Ybl-N3nnT_i6nJYbw0NJjK0j7bZHzSpqJFtJ4ugOJGM96JGCJiNykWwByhAEn4n_WBir9GvtP0nd7sHT2WqTmJ0L24cmdWM1AMTwG7rJDNid_Ks-HMa3nQV-inmsCxwOS1XjjHDXmyH0CttfQ35Wbi2DBckX-f02RbAWBix0MSaKHqRzqof2BN4HpQflwKb8fLa--nY7DqDGOpcPtNNug5n1WH45_q1ncI-IAxPTuNu8wrJLpbec8F_xtjNSO1jGHwtUSUPf23v7GhwrBmr-7y5wAb-c31F0Fi3QqF9dVzUXtjzrdrQ0rUFlAyVOpycj0JvSrWyCDIpkld8MFEoj2lmvuGW2DPIMO96C_GYgiV8lgFxaUaM4a6ZU09N8ZV4owkSeG_tryVSUp659-yi8";

		HttpRequest request = HttpRequest.newBuilder().uri(URI.create("https://api.dropboxapi.com/2/team/get_info"))
				.header("Authorization", "Bearer " + accessToken).POST(HttpRequest.BodyPublishers.noBody()).build();

		HttpResponse<String> response = client.send(request, HttpResponse.BodyHandlers.ofString());
		System.out.println("RESPONSE: "+response.body());
	}
}
